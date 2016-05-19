# Atom

Role to install Atom on an Ubuntu box

## Requirements

After downloading the role use the url on `atom/files/atom.deb.download` to download the installer and make sure its name matches the variable `ATOM_BUNDLE`.

##Role Variables

 * `ATOM_BUNDLE` - the `DEB` file at `atom/files` so installer can run, defaults to `atom.deb`.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - { role: atom, ATOM_BUNDLE: deb }

## License

MIT

## Author Information

Marco Shimomoto
