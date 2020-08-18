![alt text](https://i.imgur.com/pZ1H2xBl.png)
# Fractal-Trees
A custom Spigot tree generation plugin
## Usage
This plugin doesn't have any dependencies and should work for any Minecraft version above 1.13

## Commands and permissions
There is only one command **/tt** all the subcommands are
- /tt # Get the tool
- /tt create <args> # Create tree with arguments
- /tt info # Gets the args of the current tree
- /tt save <name> # Saves the current tree
- /tt select <name> # Select a tree
- /tt list # See the list of trees
- /tt delete # Delete a tree
- /tt undo # Undo a tree placement
- /tt help # Help command
The default tree parameters are these:
- /tt create frac 30 30 50 3 10 10 25 true OAK_WOOD OAK_LEAVES 1 1 # Default command

/tt create fractal Width Height BranchDensity BranchMinLength BranchMaxLength StemLength GrowItterations LogRotate [BranchMaterial] [LeafMaterial] LeafPerBranch BranchThickness

### Explanation
If you want to test new arguments i would suggest not changing BranchMinLength and BranchMaxLength as they can easily be changed to an invalid value. If your tree is too small, try adjusting the GrowItterations value to a higher number. For bigger trees you can change the BranchThickness to change the thickness of the stem, for smaller trees changing the branchthickness to a higher number can make the tree look weird.

### Permissions
- treegenerator.tool # /tt command
- treegenerator.tool.use # Use the tool 
- treegenerator.create DONE # Create subcommand
- treegenerator.save DONE # Save subcommand
- treegenerator.select DONE # Select subcommand
- treegenerator.info DONE # Info subcommand
- treegenerator.help DONE # Help subcommand
- treegenerator.delete DONE # Delete subcommand
- treegenerator.list DONE # List subcommand
- treegenerator.undo DONE # Undo subcommand

## Bugs and feature request
If you would like a feature to be added or have a bug, please report it [here](https://github.com/Kilrobot/Fractal-Trees/issues)

## Credits
Developed by Kilrobot, got the idea from this [video](https://www.youtube.com/watch?v=JcopTKXt8L8)

## Donations
If you would like to support me please feel free to [donate](https://www.buymeacoffee.com/kilrobot)
