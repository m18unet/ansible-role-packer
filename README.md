# Ansible Role: `packer`

An Ansible Role that installs [`packer`](https://github.com/hashicorp/packer).

## Requirements

`unzip` must be installed on the target host.

## Role Variables

Available variables are in [`defaults/main.yml`](defaults/main.yml)

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  roles:
    - m18unet.packer
```

## License

[MIT](LICENSE)

## Author Information

This role was created in 2017 by [Muhammed Kahrimanoglu](https://www.m18u.net)
