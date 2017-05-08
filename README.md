# LMiC-Arduino Library

## Usage

### Using PlatfomIO and CLion

#### Install LMiC-Arduino
If you haven't done so already, install the *LMiC-Arduino* library to the global Platformio directory of your system. This way, you won't need to install it again for future projects. If the library was already installed, make sure it is up to date. 
For more options and informations regarding libraries in PlatformIO, refer to [the documentation](http://docs.platformio.org/en/latest/userguide/cmd_update.html).
```
# Install the LMiC-Arduino library.
platformio lib -g install git@gitlab.com:smartmakers/lmic-arduino.git

# Update the LMiC-Arduino library.
platformio lib -g update git@gitlab.com:smartmakers/lmic-arduino.git
```

#### Initialize a New Project
Use the following command in an empty directory to initialize a new PlatformIO project. If required, replace `feather32u4` with the ID of the board you use (see [here](http://docs.platformio.org/en/latest/platforms/embedded_boards.html) for a full list of supported boards and their IDs). The `--ide clion` option will generate the required `CMakeList.txt` file in order to build and upload your code from CLion (see [here](http://docs.platformio.org/en/latest/ide.html) here for more information about IDE integration). 
```
# Initialize PlatformIO project.
platformio init --ide clion --board feather32u4  
```

### Using the Arduino IDE

[todo]