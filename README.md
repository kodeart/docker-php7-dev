mihailbinev/php7-dev
====================

> THIS IMAGE IS FOR DEVELOPMENT AND NOT SUITABLE FOR PRODUCTION!

* PHP7
* Supervisor
* SSHd
* PHPUnit
* Mess Detector
* CodeSniffer
* Xdebug

```sh
docker run --rm -it -p 2222:22 mihailbinev/php7-dev

# use docker-compose.yml to expose the 2222 port
# (or any other available port you like)
ssh -p 2222 root@0.0.0.0
```

