# Project Poseidon plugin template

Archived as [an official one was released](https://github.com/retromcorg/Poseidon-Plugin-Template).

Plugin template for [Project Poseidon](https://github.com/RhysB/Project-Poseidon), a Bukkit CB1060 fork.

## Instructions

1. Copy the files inside the `PoseidonPlugin` folder to your project folder.
2. Come up with a `groupID`. The default `groupID` is `org.example.poseidonplugin`, but you should replace it with your own. A good replacement would be `me.yourusername.pluginname` replacing `yourusername` and `pluginname` with your username and your plugin name, of course. Keep the plugin name in the `groupID` lowercase.
3. Come up with an `artifactID`. The `artifactID` should be the same as your plugin name in the `groupID`, but you can capitalize it as you wish here.
4. In the `src/main/java` directory, rename the folder structure inside to match your `groupID` and rename the file inside to match your `artifactID`.
5. Replace all occurences of `org.example.poseidonplugin` with your `groupID`, and all occurences of `PoseidonPlugin` with your `artifactId`. These occur in the `pom.xml`, `src/main/resources/plugin.yml`, and `src/main/java/your/group/id/YourArtifactId.java`. In the path, replace `your/group/id/` with parts of your `groupID` and `YourArtifactId` with your `artifactID`, of course.
6. Run `mvn clean package` to compile the plugin.
7. Done! You can start coding.
