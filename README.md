# Note

The below is a template for a good looking README provided by Archetype. It will be filled in with more information
as the Boulder approaches its initial release.

-----

<div align="center">
  <span align="center"> <img width="80" height="70" class="center" src="https://github.com/ChristopherNugent/Boulder/blob/master/data/images/com.github.christophernugent.boulder.png" alt="Icon"></span>
  <h1 align="center">Boulder</h1>
  <h3 align="center">Get stuff done, when it needs to be done.</h3>
</div>

<br/>

<p align="center">
    <a href="https://appcenter.elementary.io/com.github.christophernugent.boulder">
        <img src="https://appcenter.elementary.io/badge.svg">
    </a>
</p>

<p align="center">
  <a href="https://github.com/ChristopherNugent/Boulder/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-GPL-3.0-blue.svg">
  </a>
  <a href="https://github.com/ChristopherNugent/Boulder/releases">
    <img src="https://img.shields.io/badge/Release-v%201.0.0-orange.svg">
  </a>
</p>

<p align="center">
    <img  src="https://github.com/ChristopherNugent/Boulder/blob/master/data/images/screenshot.png" alt="Screenshot"> <br>
  <a href="https://github.com/ChristopherNugent/Boulder/issues/new"> Report a problem! </a>
</p>

## Installation

### Dependencies
These dependencies must be present before building:
 - `meson`
 - `valac`
 - `debhelper`
 - `libgranite-dev`
 - `libgtk-3-dev`


Use the App script to simplify installation by running `./app install-deps`
 
 ### Building

```
git clone https://github.com/ChristopherNugent/Boulder.git com.github.christophernugent.boulder && cd com.github.christophernugent.boulder
./app install-deps && ./app install
```

### Deconstruct

```
./app uninstall
```

### Development & Testing

Boulder includes a script to simplify the development process. This script can be accessed in the main project directory through `./app`.

```
Usage:
  ./app [OPTION]

Options:
  clean             Removes build directories (can require sudo)
  generate-i18n     Generates .pot and .po files for i18n (multi-language support)
  install           Builds and installs application to the system (requires sudo)
  install-deps      Installs missing build dependencies
  run               Builds and runs the application
  test              Builds and runs testing for the application
  test-run          Builds application, runs testing and if successful application is started
  uninstall         Removes the application from the system (requires sudo)
```

### Contributing

To help, access the links below:

- [Guide on Code Style](https://github.com/ChristopherNugent/Boulder/wiki/Guide-on-code-style)

- [Proposing Design Changes](https://github.com/ChristopherNugent/Boulder/wiki/Proposing-Design-Changes)

- [Reporting Bugs](https://github.com/ChristopherNugent/Boulder/wiki/Reporting-Bugs)

- [Translate](https://github.com/ChristopherNugent/Boulder/wiki/Translate)


### License

This project is licensed under the GPL-3.0 License - see the [LICENSE](LICENSE.md) file for details.
