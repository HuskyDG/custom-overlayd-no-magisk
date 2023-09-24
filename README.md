# Custom overlay.d - No Magisk

- Inject custom init.rc script without installing Magisk, put all your patch files to `overlay.d` folder. The fake `magisk` binary (compiled from [here](https://github.com/HuskyDG/sample_cpp_build/tree/fake-magisk)) is used to unmount tmpfs after booted, other Magisk's binaries I took from Official Magisk Debug version.