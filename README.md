# hello_windows_role

An Ansible role for Windows that:

- creates `C:\temp\hello.txt`
- writes `Hello`
- appends the hostname of the machine

## Requirements

- Ansible
- `ansible.windows` collection
- WinRM configured on the target host

## Example Playbook

```yaml
- hosts: windows
  roles:
    - hello_windows_role
