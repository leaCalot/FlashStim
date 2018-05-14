# FlashStim

This repository contains the design files (Eagle) and source code for the Flash Stim, a power unit that uses a Xenon Photoflash circuit as driver for the output stage. This design was inspired by discussions on various online e-stim forums.

***Before proceeding***
* You proceed at your own risk.
* You use, modify, cite, distribute everything you see under the terms of the [LICENSE](LICENSE)
* You should be experienced with electrical safety
* You should be experienced in embedded firmware and electrical circuits
* You agree to take any non-technical discussion to the appropriate [venue](reddit.com/r/estim/),
* and abide by the [code of conduct](CODE_OF_CONDUCT.md) for anything else.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them
* [Eagle (at least version 7)](https://www.autodesk.com/products/eagle/overview) - To view and edit the PCB design files
* [GNU ARM embedded (at least version 4.8)](https://developer.arm.com/open-source/gnu-toolchain/gnu-rm) - To cross-compile the sources
* [OpenOCD](http://openocd.org/) - To deploy the firmware on target.
* [ST-link debugger or equivalent](http://www.st.com/en/development-tools/st-link-v2.html) - To deploy the sources on the target.

#### Suggested Environment
* [Eclipse IDE](https://www.eclipse.org) - Versatile IDE that can be customized perform on-target debugging.
* [GDB Server](https://sourceware.org/gdb/onlinedocs/gdb/Server.html) - To provide a backhaul into the Eclipse debugger for target debugging.
* [Ubuntu 16.04](https://www.ubuntu.com/) - Leas preferred development environment. 

*Issues related to brining the system up in another development environment than above will receive a lower priority in servicing.*

### Building the Firmware

***FIXME***

A step by step series of examples that tell you have to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

### On-Target Debugging

***FIXME***

A step by step series of examples that tell you have to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Planning Documentation

* [Output Power Estimation](doc/POWER.md)

## Contributing

There is no formal process yet for contributing to this project. If you have ehnancement ideas please submit a patch as [issue](https://github.com/leaCalot/FlashStim/issues), or contact the [author](https://github.com/leaCalot) to request write privileges on this repository.

Example workflow
```
# make your edits ...
# stage your edits ...
git add my_super_awesome_fix.file
# Convert the staged files into a comprenensive patch
diff --binary --staged > my_enhancement.patch
```
Then file the ```my_enhancement.patch``` as in-line text in your [enhancement request issue](https://github.com/leaCalot/FlashStim/issues).

## Feature Roadmap

* Try Chinese BLE module to reduce cost

## Authors

* **[Lea](https://github.com/leaCalot)**

## License

This project is licensed under a modified MIT License - see the [LICENSE](LICENSE) file for details.

## Code of Conduct

Please review the [code of conduct](CODE_OF_CONDUCT.md) before engaging in discussions about this or related projects.

## Acknowledgements

* This project was inspired by discussions on Smartstim, [Socialstim](http://www.socialstim.org/), and [Reddit](https://www.reddit.com/r/estim/).
