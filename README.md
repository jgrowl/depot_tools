Description
---------------
This is a very simple oh-my-zsh plugin for installing the chromium depot_tools. Installing this plugin will put all of the chromium depot_tools in your path automatically.

Instructions
---------------

  - Clone this project in your oh-my-zsh plugins directory
  - Add depot_tools to the list of enabled plugins in your `.zshrc` file

Notes
---------------
I decided to go with git-subtree instead of git-submodule here. If this becomes out of date and you want to update you may need to manually install git-subtree because it is not currently installed by default.

Further information about the actual depot_tools can be found here on the official [depot_tools] site.


[depot_tools]: http://www.chromium.org/developers/how-tos/install-depot-tools

