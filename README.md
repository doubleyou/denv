Installation
------------

1. Install VirtualBox: https://www.virtualbox.org/wiki/Downloads
1.1. sudo chown root /Applications
1.2. sudo chmod g-w /Applications
2. Install Vagrant: http://www.vagrantup.com/downloads.html
3. Insert those lines to ~/.ssh/config:
    ```
        ServerAliveInterval 120
        TCPKeepAlive no
    ```
4. run 'denv init'
5. run 'denv new test'
6. run 'denv ssh test'

Futher actions:
7. Install homebrew
8. brew install ansible
9. Use ~/.denv/hosts to manage virtual boxes through ansible
