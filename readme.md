# debian-dev-env

>  Debian based development environment in a VM

On MacOS, you can install this with:

```bash
limactl start --progress ./debian.yaml
```

This will
* update the system
* install softwares: Neovim, zsh, Docker rootless, Mise, Claude Code, ...
* use zsh as default shell
* setup tools like docker rootless, gpg
* install the dotfiles

To enter the VM:

```bash
limactl shell debian
```
