I don't wan't to fix any bug / feature-request from MMKV side, just patch 32-bit support for Android
in this fork. If you want to publish your own fork, please update the project info in
[gradle.properties](Android/MMKV/gradle.properties) and run

```sh
# e.g. publish to maven central
./gradlew publishToMavenCentral
```

See more details about the publishing in
[vanniktech/gradle-maven-publish-plugin](https://github.com/vanniktech/gradle-maven-publish-plugin).