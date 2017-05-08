# LMiC-Arduino Library

## Usage

### Using PlatfomIO and CLion

Use the following command in an empty directory to initialize a new PlatformIO project. If required, replace `feather32u4` with the ID of the board you use (see [here](http://docs.platformio.org/en/latest/platforms/embedded_boards.html) for a full list of supported boards and their IDs). The `lib_deps` option will add the *LMiC-Arduino* library as a dependency, which will be downloaded automatically on build. The `--ide clion` option will generate the required `CMakeList.txt` file in order to build and upload your code from CLion (see [here](http://docs.platformio.org/en/latest/ide.html) here for more information about IDE integration). 
```
# Initialize PlatformIO project.
platformio init --board feather32u4 --ide clion --project-option="lib_deps=git@gitlab.com:smartmakers/lmic-arduino.git"
```

### Using the Arduino IDE

[todo]