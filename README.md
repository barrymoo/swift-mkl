# swift-mkl

This is a system library wrapper for MKL (https://software.intel.com/en-us/mkl)

Downloading MKL: https://software.seek.intel.com/performance-libraries

- Enter your information and you should be redirected to registrationcenter.intel.com
- Under "Choose Product to Download", select "Intel Math Kernel Library for {X}" where `{X}` is your OS
- Under "Choose a Version", select "2019 Update 3"
- Select "Customizable Package"

This should download a tar file with an installer. I am on Linux, so your experience may vary:

- My home directory is `/home/chiroptical`, I place code in `/home/chiroptical/src` (probably a poor naming choice in this case)
- From `/home/chiroptical/src`, `tar xvf ~/Downloads/l_mkl_2019.3.199_online.tgz` and `cd l_mkl_2019.3.199_online`
- Run `./install.sh` and follow the prompts. I chose to install into `/home/chiroptical/src/mkl`

Now you are ready to use MKL. See https://github.com/chiroptical/swift-mkl-daxpy for an example of using this library.
