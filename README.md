# ChallengePlugin
Minecraft Plugin for 1.20+ with Challenges

## Social
Discord: https://discord.gg/Vmvn5hxaUp

## Installation
1. Download the latest version of the [Plugin](https://github.com/TgZ39/ChallengePlugin/releases/).
2. Put the Plugin the the `plugins` folder of your Server.
3. Start the Server.

## Contributing

1. Clone the repository
   ```
    git clone https://github.com/TgZ39/ChallengePlugin
   ```
2. Open the created `ChallengePlugin` folder in [IntelliJ](https://www.jetbrains.com/de-de/idea/)
3. Download Java 17 (Zulu Recommended) if IntelliJ tells you to.
4. Change the `outputDirectory` in the `pom.xml` to your preferred folder.
   ```xml
   <plugin>
      <groupId>org.apache.maven.plugins</groupId>
      <artifactId>maven-jar-plugin</artifactId>
      <version>3.3.0</version>
      <configuration>
         <outputDirectory>YOUR_OUTPUT_DIRECTORY_HERE</outputDirectory>
      </configuration>
   </plugin>
   ```
5. Edit and test your code.
6. Create a [pull request](https://github.com/TgZ39/ChallengePlugin/pulls)
