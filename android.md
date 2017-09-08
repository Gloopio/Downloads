# Android

The Gloop SDK jar libraries can be found under the [release page](https://github.com/Gloopio/Downloads/releases).

## Set up

1) Download gloopProcessor-VERSION.jar and gloopSDK-VERSION.jar from [release page](https://github.com/Gloopio/Downloads/releases).

2) Copy the two libraries into the libs folder of your app.

3) Add following lines to your application `build.gradle` file under the dependencies section:

```groovy
compile fileTree(dir: 'libs', include: ['gloopSDK-*.jar'])
annotationProcessor fileTree(dir: 'libs', include: ['gloopProcessor-*.jar'])
```

## Example apps

- [Tasks App](https://github.com/Gloopio/Demo-App-Java) 
- [Drawed App](https://github.com/Gloopio/Drawed)
- [Image App](https://github.com/Gloopio/Instagram-App-Java)