# OpenIV Package Format – OIV
The OpenIV Package (OIV Package) is an archive file format for easy mod distribution. OIV Packages can be installed with OpenIV Package Installer tool. OIV Package Format is uses XML based script language for modifying game files.

OIV Package is a [ZIP archive](https://en.wikipedia.org/wiki/Zip_(file_format)) with **.oiv** or **.zip** file extension. Usually, **.zip** is used while development and testing and **.oiv** for published packages.

## Current Version - 2.2 (*Second generation*)
The current version of the OIV Package specification is [OpenIV Package Format Specification 2.2](versions/2.2.md).

### Previous Versions
This repository also contains specification for the previous versions of the OpenIV Package Format:
* [Version 2.1 Specification (*Second generation, deprecated*)](versions/2.1.md)
* Version 2.0 Specification is not available.
* [Version 1.1 Specification (*First generation, deprecated*)](versions/1.1.md)
* Version 1.0 Specification is not available.

Each folder in this repository, such as [examples](examples), should contain folders pertaining to the current and previous versions of the specification.

## OIV Package Format Generations
Currently there are two generations of OIV Package Format:
* First generation (versions: 1.1, 1.0)
* Second generation (versions: 2.2, 2.1, 2.0)

### First Generation (*deprecated, latest version 1.1*)
First generation of OIV packages. Can have multiple contents for one or several games. This version support following games:
  * Grand Theft Auto IV
  * Episodes from Liberty City
  * Max Payne 3

The only supported platform is Windows PC.

*This generation deprecated and will not evolve in future.*

### Second Generation (*current version 2.1*)
Second generation of OIV packages. Main difference from the first generation, it can contain only one content block for only one game. Also, it has additional options for controlling appearance of Package Installer.

List of supported games:
  * Grand Theft Auto IV
  * Episodes from Liberty City
  * Max Payne 3
  * Grand Theft Auto V

The only supported platform is Windows PC.
For Grand Theft Auto V, the “mods” folder also supported.

## See It in Action
If you just want to see it work, check out the [list of current examples](examples/v2.2).

## OpenIV Support
At the current moment latest version of OpenIV supports the following versions of OIV Package Format:
* Version 2.2
* Version 2.1
* Version 2.0
* Version 1.1
* Version 1.0
