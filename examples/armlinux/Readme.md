# ARM LINUX demo

## Compile: 
 * 1, cd TNN/examples/armlinux
 * 2, Build full project to get libTNN.so or libTNN.a and set TNN_LIB_PATH in build_aarch64.sh
 * 3, set CC & CXX to your needs in build_aarch64.sh
 * 4, run build_aarch64.sh and you will get binary build/demo_arm_linux

## Function：
    Create a tnn instance，and run inference. 
    input is random bgr data, output is nchw float blob
    your need to git the demo your proto and model
