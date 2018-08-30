# docker-android


------------------------
### based on [buddydeeps/dockerandroid](https://github.com/Deepsin/docker-android)
- Android
    + APIs: android-19,android-20,android-21,android-22,android-23,android-24,android-25,android-26,android-27,android-28
    + Build-Tools: 28.0.2

------------------------
## Tagging scheme
- `v${TOOLS_VERSION}-${BUILD_TOOLS_VERSION}-${HIGHEST_ANDROID_SDK_VERSION}`
- e.g. `v25.2.5-27.0.0-26`
-------------------------

### Pull from Docker Hub
docker pull buddydeeps/docker-android:latest

-------------------------

### Build from GitHub
docker build -t buddydeeps/docker-android https://github.com/Deepsin/docker-android

-------------------------
### Run image
docker run -it buddydeeps/docker-android bash

-------------------------

### Use as base image
```Dockerfile
FROM buddydeeps/docker-android:latest
```
-------------------------
