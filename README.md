# This is freertos project  on  a raspberry pi pico with the ability to access to bootsel mode 

The tools you need : pico-sdk : 

     git clone https://github.com/RaspberryPi/pico-sdk --recurse-submodules

And the Freertos-Kernel Submodules : 

    git clone -b smp https://github.com/FreeRTOS/FreeRTOS-Kernel --recurse-submodules

Add pico sdk path : 

    export PICO_SDK_PATH=$PWD/pico-sdk

Add Freertos path : 

     export FREERTOS_KERNEL_PATH=$PWD/FreeRTOS-Kernel


To access to bootsel mode : 

     sudo picotool reboot -f -u 

# if you like the project , you can donate us for more : 

    https://ko-fi.com/heyitsmeyo
