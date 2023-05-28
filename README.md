# Godot Multiplayer Dedicated Server Sample
A demo that explores Godot's high level multiplayer system, optimized for 3.5.2 Mohno.  As long as the project is not in a finished state, it will be exported as a pre-release. As of v5.0, this is the first working proof of concept release.

To download, go to the release section. Unzip the archive and place the project in the Projects directory of Godot. Use the project.godot file to open in Godot, or open the Godot binary itself and select the project.  Ensure that the port, max clients, and IP address is set. Depending if testing locally or not, the IP address will vary according to your computer's network settings.  Two ways to run include using the play button within the Godot program, or the command .\godot --path (<)project path(>) from the Godot binary location. If the code supports starting in server, then add --s header at end of command.

[cam.webm](https://github.com/Mathiaszero/Godot--Multiplayer-Dedicated-Server-Sample/assets/55817193/89daf6dc-3ba3-41ba-815d-812bd62492f7)

# Limitations
-One room only.

-Room only starts when the required player count is met; if there is less than the amount of required players, it won't start.

-Unoptimized: at current state, the code is not optimized and will cause lag, latency, and other issues when running more than 2 players.


