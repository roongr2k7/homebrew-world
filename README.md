# Homebrew World
*"The missing Homebrew command"*

Homebrew World keeps track of manually installed formulae, and safely clean orphaned dependencies when they are uninstalled.
## Installation
```
brew tap axesd9/world
```
## Basic Usage
### Install a formula, and add it to the world
```
brew world install <formula>
```
### Uninstall a formula, remove it, and automatically clean orphaned dependencies
```
brew world uninstall <formula>
```
### List all installed formulae around the world
```
brew world list
```
### Add an installed formula to the world
```
brew world add <formula>
```
### Remove an installed formula from the world
```
brew world remove <formula>
```
### Manually clean orphaned dependencies
```
brew world clean
```
### Remove all formulae from the world
```
brew world destroy
```
## Uninstallation
[Destroy the world](#remove-all-formulae-from-the-world), then
```
brew untap axesd9/world
```
