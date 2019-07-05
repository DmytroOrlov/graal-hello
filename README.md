# Build image with native-image
## (in `graalvm-native-image` subfolder)
```sh
graalvm-native-image$ docker build --tag graalvm-native-image .
```
# Build application docker image
```sh
$ sbt dockerGraalvmNative
```
# Run application
```sh
$ docker run -it --rm graal-hello
```
