# Virtual Satellite 4 - FreeCAD Module

Virtual Satellite 4 - FreeCAD Module is an extension for FreeCAD that allows to create a round-trip engineering workflow with Virtual Satellite.

## Project Status

| Master | Development |
|:------:|:-----------:|
|[![Master][master-status]][master-builds]|[![Development][development-status]][development-builds]|

[master-status]: https://travis-ci.org/FreeCAD/FreeCAD.svg?branch=master
[master-builds]: https://travis-ci.com/virtualsatellite/VirtualSatellite4-FreeCAD-mod
[development-status]: https://travis-ci.com/virtualsatellite/VirtualSatellite4-FreeCAD-mod.svg?branch=development
[development-builds]: https://travis-ci.com/virtualsatellite/VirtualSatellite4-FreeCAD-mod

## Purpose

Virtual Satellite 4 FreeCAD Module is an extension to FreeCAD. FreeCAD is an open source mechanical engineering CAD tool. The extension can be easily installed to FreeCAD. It allows to import structural configuration information into FreeCAD and keep it consistently synchronized with Virtual Satellite 

## Requirements 

This program is based on FreeCAD and Python. The following infrastructure is required:
 - FreeCAD 0.18 and higher (64bit)
 - A2plus Workbench 0.4.26 and higher
 
## Quickstart for users

If you just want to use Virtual Satellite feel free to download it from the [Releases](https://github.com/virtualsatellite/VirtualSatellite4-FreeCAD-mod/releases) section here on GitHub.

## Quickstart for developers

1. Create a new folder in the _mod_ subdirectory of FreeCAD.
2. Copy the zip file from the releases into this directory.
3. Unzip the file.
4. Start FreeCAD.

The Virtual Satellite Workbench is now available in FreeCAD

## Travis CI and Releases

Tarvis CI is set-up to start a build job for every branch and every new commit to the repository. It executes all relevant tests. Making a successful pull-request into development requires all tests to pass.

Starting a Travis CI job on development deploys all relevant artifacts.

For creating a new release, create a tag starting with *Release_* on the *master* branch. All artifacts are automatically deployed.

## Provided Features

- A new Virtual Satellite Workbench
- Functionality to uplaod a design to Virtual Satellite.
- Functionality to download a design from Virtual Satellite.

## Contribution

We are happy to receive your contributions. Nevertheless in such a big project there is a lot to respect and to obey. 
One thing to respect are legal requirements such as authorship rights and privacy protection. 
Therefore, before we can accept your contributions we need you to sign our *Contributor License Agreement (CLA)*.

Please follow the process described in *[Virtual Satellite 4 - Core](https://github.com/virtualsatellite/VirtualSatellite4-Core)* to become an authorized contributor. 

Once you are an authorized committer feel free to contribute. We will not activate your account within our organization. Therefore use Pull-Requests to contribute:

1. Create your own fork of the project.
2. Apply your changes.
3. Create a pull-request of your change to our development branch.

To increase chance that we accept your pull-request, make sure all tests are working. The best indicator is the Travis CI job. Next we will review your pull-request, give comments and maybe accept it.

## License

Copyright (C) 2019 by

   DLR (German Aerospace Center),
   Software for Space Systems and interactive Visualization
   Braunschweig, Germany

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
