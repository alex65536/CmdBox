This directory contains CmdBox component for Lazarus IDE, which provides a command line component.

The component was forked from [here](https://sourceforge.net/projects/lazarus-ccr/files/CmdLine/CmdLine%200.5.4/). The original version was written by Julian Schutsch. It was used for a long time in [Chess256](https://github.com/alex65536/Chess256), but eventually got removed from there, so now this fork exists as a standalone repository.

Changes include:
- Add a `GetText` method and `Text` property to get the text from the command line.
- Re-structure the package distribution (`example` directory for usage example, `package` directory for the package itself).
- Rewrite the `.lpk` file, add package version, authors and license.
