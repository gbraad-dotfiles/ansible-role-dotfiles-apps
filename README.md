Ansible Galaxy role: `gbraad.dotfiles-apps`
===========================================

Runs apps from my dotfiles to install applications.


## Usage

```shell
$ ansible-galaxy role install gbraad.dotfiles-apps
```

## Requirements


## Role Variables



## Dependencies


## Example Playbook

`site.yaml`
```yaml
- name: Installs brew
  hosts: localhost
  roles:
    - role: gbraad.dotfiles-apps
      vars:
        appname: brew
        action: install
```

```shell
$ ansible-playbook site.yml 
```

An example exists at [`gbraad-dotfiles/ansible-dotfiles-example`](https://github.com/gbraad-dotfiles/ansible-dotfiles-example/).


## License

MIT


## Author Information

| [!["Gerard Braad"](http://gravatar.com/avatar/e466994eea3c2a1672564e45aca844d0.png?s=60)](http://gbraad.nl "Gerard Braad <me@gbraad.nl>") |
|---|
| [@gbraad](https://gbraad.nl/social) |
