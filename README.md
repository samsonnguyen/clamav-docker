clamav-docker
=============

Simple clamav dockerfile which installs the clamav package on a centos7 image. Mainly developed to test definition databases.
For use as a scanning tool or a daemon, look at [mkodockx/docker-clamav](https://hub.docker.com/r/mkodockx/docker-clamav/) instead.

## Usage

```
docker run -v <definition_volume>:/var/lib/clamav -it samsonnguyen/clamav-docker
```

 

