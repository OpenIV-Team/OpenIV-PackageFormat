# OpenIV Package Format – OIV
## Summary
The OpenIV Package (OIV Package) is an archive file for distribution of mods. OIV Package can be installed with OpenIV Package Installer tool. OIV Package is a [ZIP archive](https://en.wikipedia.org/wiki/Zip_(file_format)) with **.oiv** or **.zip** file extension. Usually, **.zip** is using while testing package and **.oiv** for distribution to users.

There are two major version of OIV Package format:
* Version 2.1 (2.0)
* Version 1.1 (and 1.0)

## Version 2.1 (*current version*)
Second generation of OIV packages. Main difference from the first generation, it can contain only one content block for only one game. Also, it have additional options for controlling appearance of Package Installer.

List of supported games:
  * Grand Theft Auto IV
  * Episodes from Liberty City
  * Max Payne 3
  * Grand Theft Auto V

The only supported platform is Windows PC.
For Grand Theft Auto V, the “mods” folder also supported.

[Version 2.1 Specification](https://github.com/OpenIV-Team/OpenIV-PackageFormat/blob/master/specification/versions/2.1.md)

## Version 1.1 (*deprecated*)
First generation of OIV packages. Can have multiple contents for one or several games. This version support following games:
  * Grand Theft Auto IV
  * Episodes from Liberty City
  * Max Payne 3

The only supported platform is Windows PC.

*This generation deprecated and will not evolve in future.*

[Version 1.1 Specification (*deprecated*)](https://github.com/OpenIV-Team/OpenIV-PackageFormat/blob/master/specification/versions/1.1.md)

## OpenIV Support
At the current moment latest version of OpenIV supports the following versions of OIV Package Format:
* Version 1.0
* Version 1.1
* Version 2.0
* Version 2.1
