# MacroRecorder

Mod for Minecraft that helps with repetitive chores / tasks



All bug reports should be in [issues](https://github.com/Pastis444/MacroRecorder/issues).


## Building

This project is now built on [this template](https://github.com/romangraef/Forge1.8.9Template/). Build instructions from there: 

> To run the mod you will need two JDKs, one Java 17 jdk and one Java 1.8 jdk.

> When you import your project into IntelliJ, you need to set the gradle jvm to the Java 17 JDK in the gradle tab, and the Project SDK to the Java 1.8 JDK. Then click on the sync button in IntelliJ, and it should create a run task called Minecraft Client. If it doesn't then try relaunching your IntelliJ. Warning for Mac users: You might have to remove the -XStartOnFirstThread vm argument from your run configuration.

You can also build in the command line. Set your JAVA_HOME environment variable to the path to the 1.8 JDK and then run

```
./gradlew build -Dorg.gradle.java.home=/PATH/TO/JDK17
```
