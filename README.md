# docker-freshclam
A simple ClamAV Freshclam daemon docker instance based on Alpine

### To pull container

```docker pull hyperized/freshclam```

### To build container

```docker build -t freshclam .```

### To run container 

```docker run -p 3310:3310 freshclam```

Inspired by: [mko-x/docker-clamav](https://github.com/mko-x/docker-clamav)