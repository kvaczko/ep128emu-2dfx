This fork currently builds the original ep128emu on Ubuntu using GitHub Actions.
The Linux CI build uses SCons with:
scons -j2 nosdl=1 nolua=1 curl=0 utils=0 release=0 nopkgconfig=1
