## Scala Console Starter

TODO: Reminder to myself on a minimal starting point for a console app in Scala


### Prerequisites

1. Docker

    + [Windows] (https://docs.docker.com/docker-for-windows/install/)
    + [Mac] (https://download.docker.com/mac/stable/Docker.dmg)


### Up & Running


Perform continuous compile of the local project with,

```
docker-compose up
```

If you need to adjust the version of scala referenced in docker-compose.yml, visit https://hub.docker.com/r/hseeberger/scala-sbt/tags to identify the image you need.

Run the app with something like `docker exec -it scala-console-starter_build_1 scala ./build/console.jar`
