# FourthFloorTSRBGazeboWorld

Gazebo world representing the 4th floor of the Tech Square Research Building (TSRB). Created for Georgia Tech TerraBots VIP team.

The original Gazebo world for the 4th floor of the TSRB was taken from here https://github.com/ivaROS/navigation_test. This repository includes an updated Gazebo world with additional obstacles, furniture, texturing, and resources.

### Setup
1. Make sure you have Gazebo installed on your computer. See here https://trello.com/c/VWUTJQsR/87-fletcher-2022sp for instructions on Mac installation.
2. Clone the GitHub repository. Download the zip or run `git clone https://github.com/wellsfletcher/FourthFloorTSRBGazeboWorld.git` within terminal.
3. **Important: move the files within `FourthFloorTSRBGazeboWorld/models/` to your local Gazebo models folder.** On my Mac computer, this location is `~/.gazebo/models/`. On a Mac, you can navigate to this folder within finder by pressing `shift command g` and entering `~/.gazebo/models/`. It may help it show hidden files and folders by entering `shift command .`.
4. Navigate to your local copy of `FourthFloorTSRBGazeboWorld` within Terminal. Enter `gazebo fourth_floor.world`.
5. If you have done everything correctly, your world should look like this: ![full](https://user-images.githubusercontent.com/30359960/166334726-df1587db-0632-418e-8869-93684d53b0ee.jpg)

### What's included in this repo
- `models/` The models used in the `fourth_floor.world` Gazebo world plus some extra ones. The majority of these models were obtained from https://data.nvision2.eecs.yorku.ca/3DGEMS/.
- `fourth_floor.world` The main Gazebo file used to represent the fourth floor of the TSRB.
- `references/` A backup folder containing files I created or referenced while trying to create the TSRB fourth floor world. None of these files are needed to run the `fourth_floor.world` file.
  - `FourthFloorTSRB.blend` Blender file containing the work I did to recreate the fourth floor within Blender using the "Archimesh" addon. Make sure you enable the "Archimesh" addon within Blender settings before attempting to edit this file.
  - `Floor.blend` Blender file used to create the floor model that appears in the Gazebo world.
  - `maps/` Folder containing images representing the layout of the fourth floor of the TSRB.

### Additional resources
- https://docs.google.com/presentation/d/1ElLLTqRQE16Dux6uiVr3GwRFHl_71B5ckcPgHxqvEUo/edit?usp=sharing
- https://trello.com/c/VWUTJQsR/87-fletcher-2022sp
- https://github.com/ivaROS/navigation_test
- https://data.nvision2.eecs.yorku.ca/3DGEMS/
