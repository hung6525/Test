Reference:  https://gist.github.com/cjtallman/b526d8c7d8b910ba4fd41eb51cd5405b

# Vagrant Gitlab Server

Quickly set up a local Gitlab CE server using Vagrant.

Run `vagrant up` to setup the virtual server.

# Server Details

- Ubuntu 16.04
- Installs latest Docker
- Installs latest Gitlab CE
- Installs latest Gitlab Multi Runner
- Server at http://33.33.33.33 (http://gitlab.local.dev)

-------------------------------------------

vagrant ssh      #into gitlab server

sudo gitlab-ctl status

sudo vi /etc/gitlab/gitlab.rb    # configure file and will have gitlab fqdn.

# First time to Gitlab url will prompt for new password for ROOT user
# After new password created, login as root and new password.


Example:
https://www.youtube.com/watch?v=O7jgl0rWUlE
