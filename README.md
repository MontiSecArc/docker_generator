# About
MontiSecArc architectures include information also required to define Docker Compose image definitions. By extracting the structural information from MSA files and creating Docker Compose files the developer can focus on the details of the system.

**Downloads**

[DockerGenerator-1.0-SNAPSHOT.zip](http://138.68.65.103:8081/artifactory/intellij_plugins_snapshot_local/de/monticore/lang/montisecarc/generator/docker/DockerGenerator/1.0-SNAPSHOT/DockerGenerator-1.0-SNAPSHOT.zip) &#8226; [DockerGenerator-1.0-SNAPSHOT.jar](http://138.68.65.103:8081/artifactory/intellij_plugins_snapshot_local/de/monticore/lang/montisecarc/generator/docker/DockerGenerator/1.0-SNAPSHOT/DockerGenerator-1.0-SNAPSHOT.jar)

# Contents
- [Quickstart](https://git.rwth-aachen.de/ma_buning/docker_generator/edit/master/README.md#quickstart)
- [Install Plugin into IntelliJ Installation](https://git.rwth-aachen.de/ma_buning/docker_generator/edit/master/README.md#install_plugin_into_intelliJ_installation)

# Quickstart
1. Check-Out project:

    `git clone https://git.rwth-aachen.de/ma_buning/msa.git --remote --recursive`
2. Import project into IntelliJ. Instructions can be found [here](https://www.jetbrains.com/help/idea/2016.3/importing-project-from-gradle-model.html).
3. Run an IDEA instance with the MSA language plugins pre-installed:
    1. Run/Debug `runIdea` from the gradle task list:
    ![Bildschirmfoto_2017-01-10_um_18.28.47](/uploads/a8260570e6023b852a4d72124ba07b32/Bildschirmfoto_2017-01-10_um_18.28.47.png)
4. This plugin includes a new entry in the *Generate* context menu of MSA files, where you now can select **Generate Docker File**

# Install Plugin into IntelliJ Installation
The plugin requires IntelliJ Version [2016.X.X](https://www.jetbrains.com/idea/download/) to be installed.

Download the newest version of the plugin from [here](http://138.68.65.103:8081/artifactory/intellij_plugins_snapshot_local/de/monticore/lang/montisecarc/generator/docker/DockerGenerator/1.0-SNAPSHOT/DockerGenerator-1.0-SNAPSHOT.zip). Do not unzip the file, just open the IntelliJ preferences and locate "Plugins" from the left menu.
![Bildschirmfoto_2016-11-11_um_09.38.51](/uploads/f4193ddd5d0af2de84b787314bcdaade/Bildschirmfoto_2016-11-11_um_09.38.51.png)
Click the "Install plugin from disk" button and select the downloaded zip file.