ssh
===

[![Build Status](https://travis-ci.org/dotstrap/ansible-ssh.svg)](https://travis-ci.org/dotstrap/ansible-ssh)

Configure ssh.

Requirements
------------

None.

Role Variables
--------------

See [default variables].

Dependencies
------------

None.

Example Playbook
----------------

Using all the [default variables]:

```
    - hosts: servers
      roles:
         - role: dotstrap.ssh
           ssh_hosts:
             foo:
                 user: 'foo_user'
                 hostname: '124.16.254.1'
             bar:
                 user: 'bar_user'
                 hostname: 'bar.example.com'
```

License
-------

MIT

Author Information
------------------

[@mwilliammyers]

[@mwilliammyers]: https://github.com/mwilliammyers
[aura]: https://github.com/aurapm/aura
[default variables]: defaults/main.yml
[dotstrap]: https://github.com/mwilliammyers/dotstrap
[fasd]: https://github.com/clvv/fasd
[files]: files/
[fish]: http://fishshell.com/
[homebrew]: https://github.com/Homebrew/homebrew
[pacaur]: https://github.com/rmarquis/pacaur
[pacman]: https://www.archlinux.org/pacman/
[variables]: vars/
[yaourt]: https://github.com/archlinuxfr/yaourt
[zsh]: http://zsh.sourceforge.net
