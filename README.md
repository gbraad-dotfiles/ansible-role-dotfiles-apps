Ansible Galaxy role: `gbraad.dotfiles-apps`
===========================================

Runs `app` from my dotfiles to install applications according to the [application defintions](https://github.com/gbraad-dotfiles/applications). These are Actionfiles specifically to handle application related tasks, like installation, service install, desktop export, etc.


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
        appname: codium-server
        action: install
```

> [!NOTE]
> `action: install` can be omitted as this is the default

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
