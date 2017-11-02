# docker-debian-git-w-git-ftp
A minimal docker container with debian, git, and
git-ftp for automated deploy inside bitbucket-pipelines.

Secure FTP is required, though can be changed to insecure ftp by
uncommenting one line in Dockerfile.


# Source
Original source: https://github.com/SamuelDebruyn/docker-debian-git

Modification:
 * Added git-ftp
 * Added and commented-out secure ftp (from another fork)
 * Additional Documenation

 [![docker](http://dockeri.co/image/bhartlbgrt/docker-debian-git-w-git-ftp "docker")](https://registry.hub.docker.com/u/bhartlbgrt/docker-debian-git-w-git-ftp/)
