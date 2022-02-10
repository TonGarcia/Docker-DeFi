# DappTools on Docker

Dockerfile source code & tutorial:
https://gist.github.com/kathodler/8488594509cfbd28c2fcce8437a0f6aa

## Steps

1. (off) Find user uid: ``` id YOUR_USERNAME_AT_COMPUTER ```
1. (off) Change user uid in the Dockerfile ``` ENV UID=1000 & GID=1000 ```
1. Build: ``` $ docker-compose build ```
1. Run: ``` $ docker-compose run dt --version ```