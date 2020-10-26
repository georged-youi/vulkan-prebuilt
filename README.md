This repository contains a copy of prebuilt binaries and headers from
the Vulkan SDK. This is being done to allow prebuilt Vulkan libraries
to be pulled in by Hunter.

# Supported platforms

- OSX

# Source Packages

The prebuilt binaries contained in the repository are copied directly
from official Vulkan SDK releases. The following lists the various
releases used, as well as their versions.

## MacOS

Filename: [vulkansdk-macos-1.2.154.0.dmg](https://vulkan.lunarg.com/sdk/home#sdk/downloadConfirm/1.2.154.0/mac/vulkansdk-macos-1.2.154.0.dmg)

MD5: `f0fea776e02ac92dbb47ba8bdad4130c`

# Porting and Testing

The script `build.sh` can be used to build the library and 'install' it
to the `install/` folder for the current platform.

To test, the script `test/build.sh` can be used. That script builds a
simple test program that links to the 'installed' library, again for the
current platform. It is necessary for the library to have been built
before running the test build script.
