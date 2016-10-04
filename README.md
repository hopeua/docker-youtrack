# YouTrack image

[![hope/youtrack](https://img.shields.io/badge/docker-hope/youtrack-brightgreen.svg)](https://hub.docker.com/r/hope/youtrack/)

Simple Jetbrains YouTrack deployment.  
https://www.jetbrains.com/youtrack/

## Run

    docker run -p 8080:8080 hope/youtrack
    
### Enviroment variables

**YOUTRACK_PORT** – public port for app (default 8080)

**JAVA_mx** – maximum heap memory size (default 1gb)

**APP_*** – YouTrack Java start parameters ([full list](https://www.jetbrains.com/help/youtrack/standalone/7.0/YouTrack-Java-Start-Parameters.html)). Replace **.** with **_** when using in env variables.
