TOP=..
include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#=============================

# Note, the files in this directory were manually copied from the Andor SDK3 directories 
# for Linux and Windows.  The soft links for Linux were manually created.

INC += atcore.h
INC += atutility.h

ifeq (win32-x86, $(findstring win32-x86, $(T_A)))
LIB_INSTALLS_WIN32    += ../os/win32-x86/atcorem.lib

else ifeq (windows-x64, $(findstring windows-x64, $(T_A)))
LIB_INSTALLS_WIN32    += ../os/windows-x64/atcorem.lib

else ifeq (linux-x86_64, $(findstring linux-x86_64, $(T_A)))
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so.3
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevregcam.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevregcam.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatusb_libusb10.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatusb_libusb10.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatblkbx.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatblkbx.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcl_bitflow.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcl_bitflow.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevapogee.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevapogee.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevchamcam.so.3.15.30004.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevchamcam.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevsimcam.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevsimcam.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatutility.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatutility.so.3
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatutility.so

else ifeq (rhel6-x86_64, $(findstring rhel6-x86_64, $(T_A)))
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so.3.15.30092.2
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so.3
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so

else ifeq (rhel7-x86_64, $(findstring rhel7-x86_64, $(T_A)))
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so.3
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevregcam.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevregcam.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatusb_libusb10.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatusb_libusb10.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatblkbx.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatblkbx.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcl_bitflow.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcl_bitflow.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevapogee.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevapogee.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevchamcam.so.3.15.30004.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevchamcam.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevsimcam.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevsimcam.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatutility.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatutility.so.3
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatutility.so

else ifeq (rhel9-x86_64, $(findstring rhel9-x86_64, $(T_A)))
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so.3
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevregcam.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevregcam.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatusb_libusb10.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatusb_libusb10.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatblkbx.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatblkbx.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcl_bitflow.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcl_bitflow.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevapogee.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevapogee.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevchamcam.so.3.15.30004.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevchamcam.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevsimcam.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevsimcam.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatutility.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatutility.so.3
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatutility.so

else ifeq (linuxRT-x86_64, $(findstring linuxRT-x86_64, $(T_A)))
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so.3
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcore.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevregcam.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevregcam.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatusb_libusb10.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatusb_libusb10.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatblkbx.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatblkbx.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcl_bitflow.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatcl_bitflow.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevapogee.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevapogee.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevchamcam.so.3.15.30004.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevchamcam.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevsimcam.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatdevsimcam.so
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatutility.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatutility.so.3
LIB_INSTALLS_Linux += ../os/linux-x86_64/libatutility.so

else ifeq (linux-x86, $(findstring linux-x86, $(T_A)))
LIB_INSTALLS_Linux += ../os/linux-x86/libatcore.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86/libatcore.so.3
LIB_INSTALLS_Linux += ../os/linux-x86/libatcore.so
LIB_INSTALLS_Linux += ../os/linux-x86/libatdevregcam.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86/libatdevregcam.so
LIB_INSTALLS_Linux += ../os/linux-x86/libatusb_libusb10.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86/libatusb_libusb10.so
LIB_INSTALLS_Linux += ../os/linux-x86/libatblkbx.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86/libatblkbx.so
LIB_INSTALLS_Linux += ../os/linux-x86/libatcl_bitflow.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86/libatcl_bitflow.so
LIB_INSTALLS_Linux += ../os/linux-x86/libatdevapogee.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86/libatdevapogee.so
LIB_INSTALLS_Linux += ../os/linux-x86/libatdevchamcam.so.3.15.30004.0
LIB_INSTALLS_Linux += ../os/linux-x86/libatdevchamcam.so
LIB_INSTALLS_Linux += ../os/linux-x86/libatdevsimcam.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86/libatdevsimcam.so
LIB_INSTALLS_Linux += ../os/linux-x86/libatutility.so.3.15.30126.0
LIB_INSTALLS_Linux += ../os/linux-x86/libatutility.so.3
LIB_INSTALLS_Linux += ../os/linux-x86/libatutility.so

endif

#=============================

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

