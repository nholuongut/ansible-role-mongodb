# ansible-role-mongo #

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

An Ansible role for installing [MongoDB](https://www.mongodb.com/).

## Requirements ##

None.

## Role Variables ##

None.

<!--
| Variable | Description | Default | Required |
|----------|-------------|---------|----------|
| optional_variable | Describe its purpose. | `default_value` | No |
| required_variable | Describe its purpose. | n/a | Yes |
-->

## Dependencies ##

- [nholuongut/ansible-role-disable-numa](https://github.com/nholuongut/ansible-role-disable-numa)
- [nholuongut/ansible-role-disable-thp](https://github.com/nholuongut/ansible-role-to-disable-transparent-huge-pages)
- [nholuongut/ansible-role-numactl](https://github.com/nholuongut/ansible-role-for-installing-numactl)
- [nholuongut/ansible-role-pip](https://github.com/nholuongut/ansible-role-for-installing-pip)
- [nholuongut/ansible-role-python](https://github.com/nholuongut/ansible-role-for-installing-python)

## Example Playbook ##

Here's how to use it in a playbook:

```yaml
- hosts: all
  become: yes
  become_method: sudo
  tasks:
    - name: Install MongoDB
      ansible.builtin.include_role:
        name: mongo
```

## Contributing ##

We welcome contributions!  Please see [`CONTRIBUTING.md`](CONTRIBUTING.md) for
details.

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
