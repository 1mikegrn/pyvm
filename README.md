# Python Version Manager

Uses a python docker container to create a local virtual environment.

place pyvm in a folder on path, and use as follows:

`sudo pyvm <version>`

script will download docker container corresponding to the version specified,
move the contents of the /usr/local directory to a ./venv directory, and add an
activation script. activation script has the same action as the `venv`
activation script, but also includes env flags for specifying .so library
directories.

