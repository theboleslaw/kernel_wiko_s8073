To Fix :
========

s8073.mk

mymake



export PATH=~/Your_Toolchain_PATH/ 
for_example  /alps/prebuilt/linux-x86/toolchain/arm-linux-androideabi-4.4.x/bin:$PATH

Buile command:

kernel
======
cd <kernel path>
cp mediatek-configs .config
TARGET_PRODUCT=s8073 MTK_ROOT_CUSTOM=../mediatek/custom make
