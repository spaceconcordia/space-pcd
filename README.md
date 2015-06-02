space-pcd
=========

# Config Files
pcd.X.X.X/.config contains the default configuration
config_Q6 and config_x86 are auto-generated, and should not be modified

# Building

You must provide the full path to the MBCC cross-compiler for unknown reasons (it is already on the path, but can't be found during compilation)
It seems the CONFIG_PCD_CROSS_COMPILER_PREFIX flag in .config is in fact the default build environment, not an additional compiler. TODO, it would be nice to selectively build Q6 or x86 for testing
