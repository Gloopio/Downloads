# Android

## Set up

1) Download gloopProcessor-VERSION.jar and gloopSDK-VERSION.jar from [release page](https://github.com/Gloopio/Downloads/releases).

2) Copy the two libraries into the libs folder of your app.

3) Add following lines to your application `build.gradle` file under the dependencies section:

```
compile fileTree(dir: 'libs', include: ['gloopSDK-*.jar'])
annotationProcessor fileTree(dir: 'libs', include: ['gloopProcessor-*.jar'])
```
