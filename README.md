## chip-linux-cc
CHIP linux kernel cross compile environment

### Docker image for build environment

I recently built some docker images with the environment to build a kernel.

The images are based on Ubuntu 16.04LTS and include all the build environment and the git repo for kernel 4.3 and 4.4.11.

In the simple case, run the image of choice as instructed to prompt for menuconfig and build a custom kernel.

### For a future iteration

A challenge set forth here is to alter the dockerfile in such a way that it can be made to function in the manner of <a href="https://github.com/GoogleContainerTools/distroless">distroless</a>.
