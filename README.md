# simplesftp
Simple sftp server using Docker (atmoz/sftp)

usage: sftpdocker [start | stop | manage]
    start: create and run atmoz/sftp server
    restart: stop & start
    stop: stop and remove atmoz/sftp server
    manage: attach shell to atmoz/sftp server

user.conf: atmoz/sftp user infos

/home: atmoz/sftp home directory
ex] /home/user0: user0's home directory

Refer to https://github.com/atmoz/sftp
