# Android Starter
A Starter Android Project using Gradle

## Prerequisites
To develop Android applications, you need to install Android SDK.

## How to Create Android Apps
This starter project name is *Starter*. Its domain is *com.example.starter*. Please rename it to fit your own project name and domain.

1. Make sure you have correct structure below _app/src/main/java/_ based on your domain. For example, your domain is _com.example.starter_, then your should have _app/src/main/java/com/example/starter/MainActivity.java_.
2. Make sure the package name in _MainActivity.java_ file at first line matchs your domain.
3. You may also need to check _app/src/androidTest/java_ to matchs your domain.
4. You may also need to check _ApplicationTest.java_ file at first line matchs your domain.
5. See _AndroidManifest.xml_ in manifest tag. Check its 'package' attribute.
6. See _app/build.gradle_ and check 'applicationId'
7. Rename _location.properties.example_ to _location.properties_. Set _sdk.dir_ to your Android SDK path.

## How to Build

Simply run `./gradlew assembleDebug`. At first time, it will download gradle and some dependencies. Please wait for minutes. Downloading is only done once.

Run `./gradlew tasks` to list available tasks.