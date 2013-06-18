Description
---------------
This is a very simple oh-my-zsh plugin for installing the chromium depot_tools. Installing this plugin will put all of the chromium depot_tools in your path automatically.

Instructions
---------------

  - Clone this project in your oh-my-zsh plugins directory
  - Add depot_tools to the list of enabled plugins in your `.zshrc` file

Notes
---------------
If depot_tools becomes out of date, update depot_tools by running the following:

git pull -s subtree depot_tools master

Further information about the actual depot_tools can be found here on the official [depot_tools] site. Here is the git remote [depot_tools_git]


[depot_tools]: http://www.chromium.org/developers/how-tos/install-depot-tools
[depot_tools_git]: https://chromium.googlesource.com/chromium/tools/depot_tools.git

