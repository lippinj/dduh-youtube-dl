This package is part of an exercise for the
[Devops with Docker](https://devopswithdocker.com/part1/) course.
The aim of the exercise is to publish a youtube-dl container on Docker Hub.

To use the container, mount a volume at `/download`,
and pass the target URL as an argument.
For example:

```
docker run -v "$(pwd):/download" alcedine/youtube-dl https://imgur.com/JY5tHqr
```
