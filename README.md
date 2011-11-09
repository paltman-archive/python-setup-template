# README

This is what I use to package up Python (mostly Django apps) packages.

## Usage

* git clone https://paltman@github.com/paltman/python-setup-template.git
* cd your-project-directory
* Make sure your package is not at the root of your project directory
  (e.g. your-project-directory/your\_package)
* cp -r ../python-setup-template/\* .
* Doing this you should end up with a setup.py and docs/ as peers to your
  your\_package directory.
* Edit the docs/Makefile and change the name of the PROJECT variable
  to match your package name.
* Edit the docs/conf.py and set the different variables to the approprate
  values.
* Write your documentation you can use the provided stubs, but they are
  mostly what I use to document Django apps so I leave them in here.
