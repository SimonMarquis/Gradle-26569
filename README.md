# Gradle issue [#26569](https://github.com/gradle/gradle/issues/26569)

1. Configure repository in [build.gradle.kts#L11](build.gradle.kts#L11)
2. Run the build command
   ```bash
   ./gradlew build --no-configuration-cache --refresh-dependencies
   ```
 