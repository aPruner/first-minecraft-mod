# First Minecraft Mod

This is a minecraft mod project based on forge v1.15! I've created this project by downloading the MDK from [here](http://files.minecraftforge.net/).

### Running the project with Intellij Idea (on Windows)

1. To open the project, import the `build.gradle` file.
2. Ensure you have a JDK installed (version 11 or older) and `JAVA_HOME` environment variable set. For instructions on how to do this, go [here](https://www3.ntu.edu.sg/home/ehchua/programming/howto/JDK_HowTo.html).
3. Open up a CMD and cd to your project root (from where you ran `git clone`, run `cd first-minecraft-mod`), then run `gradlew genIntellijRuns`.
4. In Intellij Idea, (this will be different on Mac/Linux) go to File -> Reload all from disk. Then, go to File -> New Projects Settings -> Structure for New Projects. Select the JDK (version 11 or older) that you installed. If you skipped step 2 you can get the JDK from this window, but you will have to manually set the `JAVA_HOME` environment variable afterwards in Windows.
5. The run configurations should now be setup for you. In Intellij Idea, go to Run -> Run (or hit the green play button) and run the `runServer`, and `runData` configurations. Then, run the `runClient` config.
6. Happy modding!