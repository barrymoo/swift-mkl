# swift-mkl

This is a system library wrapper for MKL (https://software.intel.com/en-us/mkl)

Downloading MKL: https://software.seek.intel.com/performance-libraries

- Enter your information and you should be redirected to registrationcenter.intel.com
- Under "Choose Product to Download", select "Intel Math Kernel Library for {X}" where `{X}` is your OS
- Under "Choose a Version", select "2019 Update 3"
- Select "Customizable Package"

This should download a tar file with an installer. I am on Linux, so your experience may vary:

- My home directory is `/home/barrymoo`, I place code in `/home/barrymoo/src` (probably a poor naming choice in this case)
- From `/home/barrymoo/src`, `tar xvf ~/Downloads/l_mkl_2019.3.199_online.tgz` and `cd l_mkl_2019.3.199_online`
- Run `./install.sh` and follow the prompts. I chose to install into `/home/bmooreii/src/mkl`

Now you are ready to use MKL. See https://github.com/barrymoo/swift-mkl-daxpy for an example of using this library.
