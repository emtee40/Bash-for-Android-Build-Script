# Build Bash for Android

A script that patches & cross-compiles bash for Android

## Prerequisites

* Android NDK (tested w/ r18b)
* Linux or Linux WSL on W10 (tested on Ubuntu WSL on W10 Pro)
* GNU Make

## Compile

	$ git clone ...
  $ ./build-bash.sh <options>

## Notes

  The android patches are for bash 4.4-23 stable. If you're compiling any other version of bash, make sure the patch files are targeting the correct lines (use check argument)
  
  If building fails, you likely need to add/remove/modify patches. Just place the patches in the patches folder and the script will apply them
  
## License

  MIT