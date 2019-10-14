## STM32MPU_EmbSW_Android_Overall_Offer Overview


**STM32MPU Embedded Software distribution for Android™** is a set of software components, system build and development tools created to ease the development to be done on top of STM32MPU devices.


**STM32MPU Embedded Software distribution for Android™** is provided as **demonstrator**.
In this context, the Android™ certifications are not insured.


**STM32MPU Embedded Software distribution for Android™** includes:
* A distribution for Android™, running on the Arm® Cortex®-A processor(s) : [STM32MPU distribution for Android](https://wiki.st.com/stm32mpu/wiki/STM32MPU_distribution_for_Android)
* A STM32Cube Package, running on the Arm® Cortex®-M processor : [STM32Cube package](https://wiki.st.com/stm32mpu/index.php/STM32CubeMP1_Package)

**STM32MPU distribution for Android™** includes the following collection of software components:
* OpenSTLinux BSP (OP-TEE secure OS, boot chain and Linux kernel):
  * The boot chain based on TF-A and U-Boot
  * The OP-TEE secure OS running on the Cortex®-A in secure mode
  * The Linux kernel running on the Cortex®-A in non-secure mode
* Application frameworks composed of middleware components relying on the BSP and providing a set of APIs:
  * Android APIs to run Applications that typically interact with the user via a display or a touchscreen.
  * OP-TEE APIs to run Trusted Applications (TA) that allow manipulating secrets (information not visible from Linux® and from the STM32Cube MPU Package)

**STM32Cube™** is a comprehensive embedded software libraries and drivers, delivered for each STM32 series.
   * The CMSIS modules (core and device) corresponding to the Arm® core implemented in this STM32 product
   * The STM32 HAL-LL drivers : an abstraction drivers layer, the API ensuring maximized portability across the STM32 portfolio
   * The BSP Drivers of each evaluation or demonstration board provided by this STM32 series
   * A consistent set of middlewares components such as RTOS, OpenAMP, ...
   * A full set of software projects (basic examples, applications or demonstrations) for each board provided by this STM32 series

## Description

This repo is a simple Readme describing all STM32MP1 related GitHub projects, the open source offer for the STM32 MPU products.

### STM32MPU Embedded Software for Android packages
STM32MP1 Packages for Android | Description
----------------------------- | -----------
[android-manifest](https://github.com/STMicroelectronics/android-manifest) | STM32MP1 Embedded Software for Android overall manifest
[device-stm-bootloader](https://github.com/STMicroelectronics/device-stm-bootloader.git) | BSP (TF-A and U-Boot bootloader)
[device-stm-kernel](https://github.com/STMicroelectronics/device-stm-kernel.git) | BSP (Linux kernel)
[device-stm-tee](https://github.com/STMicroelectronics/device-stm-tee.git) | BSP (OP-TEE)
[device-stm-openocd](https://github.com/STMicroelectronics/device-stm-openocd.git) | BSP (openocd for debug)
[device-stm-common](https://github.com/STMicroelectronics/device-stm-common.git) | STM32MP1 configuration
[device-stm-eval](https://github.com/STMicroelectronics/device-stm-eval.git) | STM32MP17c-EV1 configuration
[hardware-peripheral-allocator](https://github.com/STMicroelectronics/hardware-peripheral-allocator.git) | allocator hardware interface
[hardware-peripheral-audio](https://github.com/STMicroelectronics/hardware-peripheral-audio.git) | audio hardware interface
[hardware-peripheral-bootctrl](https://github.com/STMicroelectronics/hardware-peripheral-bootctrl.git) | bootctrl hardware interface
[hardware-peripheral-camera](https://github.com/STMicroelectronics/hardware-peripheral-camera.git) | camera hardware interface
[hardware-peripheral-composer](https://github.com/STMicroelectronics/hardware-peripheral-composer.git) | composer hardware interface
[hardware-peripheral-copro](https://github.com/STMicroelectronics/hardware-peripheral-copro.git) | copro hardware interface
[hardware-peripheral-health](https://github.com/STMicroelectronics/hardware-peripheral-health.git) | health hardware interface
[hardware-peripheral-lights](https://github.com/STMicroelectronics/hardware-peripheral-lights.git) | lights hardware interface
[hardware-peripheral-memtrack](https://github.com/STMicroelectronics/hardware-peripheral-memtrack.git) | memtrack hardware interface
[hardware-peripheral-oemlock](https://github.com/STMicroelectronics/hardware-peripheral-oemlock.git) | oemlock hardware interface
[hardware-peripheral-thermal](https://github.com/STMicroelectronics/hardware-peripheral-thermal.git) | thermal hardware interface
[hardware-peripheral-usb](https://github.com/STMicroelectronics/hardware-peripheral-usb.git) | usb hardware interface
[hardware-peripheral-wifi](https://github.com/STMicroelectronics/hardware-peripheral-wifi.git) | wifi hardware interface
[coproservice](https://github.com/STMicroelectronics/packages-apps-coproservice.git) | coprocessor service
[vendor-stm-app](https://github.com/STMicroelectronics/vendor-stm-app.git) | application and firmware packages

## Communication and support
For communication and support, you can use
* [ST Support Center](https://my.st.com/ols#/ols/) for any defect
* [ST Community MPU](https://community.st.com/stm32mpu) forum
