# Run a cron job in a docker container

Adapt this Dockerfile to your needs when running regular commands from within a Docker image.
This repo is inspired by this post from [Julien Boulay](https://www.ekito.fr/people/run-a-cron-job-with-docker/)

## Getting started

### Run the image as is for a demo

```shell
sudo docker run -it patrickmerlot/cronjob_demo
```

### Build the image

```shell
sudo docker build --rm -t patrickmerlot/cronjob_demo .
```

### Sending reports/alert by email

[coming soon]


