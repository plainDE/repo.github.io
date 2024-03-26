# plainDE Debian Repository

HOW-TO:

1. `wget -qO - http://plainde.github.io/repo.github.io/key.gpg | apt-key add -`
2. `echo "deb http://plainde.github.io/repo.github.io/debian/ /" > /etc/apt/sources.list`
3. apt update
4. apt install plainde-meta
