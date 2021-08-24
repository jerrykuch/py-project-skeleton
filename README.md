# Python Barebones Project Skeleton

To use:
  * Copy this skeleton directory somewhere and rename it after your project
  * Rename the `NAME` subdirectory with the root *module name* you want
  * Edit `setup.py` to have information for your project
  * Rename `tests/NAME_tests.py` to have your module name
  * Run tests for sanity check:  Run `nosetests` in topmost directory
  of project
  * Delete the `.git` directory
  * Start coding!

# Things To Elaborate On Further

  * Dig into `setup.py` and see the functionality it offers (clumsily
  and weirdly)
  * Look into [`distutils`](http://docs.python.org/distutils/setupscript.html)
  * Make a project and start putting code into the module
  * Put a script in `bin` that can be run since `bin` is a standard
    place to put scripts that are run from the CLI
  * Mention the script in `bin` in `setup.py` so it gets installed
  * Use `setup.py` to install the module, make sure it works, and then
  use `pip` to uninstall it


