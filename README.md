# jmc-rules
Flight Recorder Custom Rule that throws an Exception when is evaluated according to the bug https://bugs.openjdk.java.net/browse/JMC-5767

To run flame-rules plugin:
1. Import the JMC project into Eclipse.
2. Don't forget to import the launchers.
3. Copy and rename one of the launchers (for example the JMC RCP plug-ins launcher), to have your own launcher configuration.
4. Import the two eclipse projects from the repository (the plug-in and the feature projects) from this repo into your eclipse worksapce.
5. Add org.openjdk.jmc.feature.flightrecorder.rules.sample to the features to launch in your launcher.
6. Launch JMC from within Eclipse with your new launcher.

useful: Developing OpenJDK Mission Control: http://hirt.se/blog/?p=989