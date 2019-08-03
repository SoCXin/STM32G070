# [STM32G070](https://www.soc.xin/STM32G070)

* [ST](https://www.st.com/zh/): [Cortex-M0](https://github.com/SoCXin/Cortex)
* [L2R2](https://github.com/SoCXin/Level): 64 MHz , [￥5.07 (LQFP-64)](https://item.szlcsc.com/549618.html)

## [简介](https://github.com/SoCXin/STM32G070/wiki)

[STM32G070](https://www.st.com/zh/microcontrollers-microprocessors/stm32g0-series.html)是目前ST最具性价比的低成本MCU产品，拥有出色的性能和完善的开发资源，在该级别产品中拥有非常出色的表现。

[![sites](docs/STM32G070.png)](https://www.soc.xin/STM32G070)

### 关键参数

* 64 MHz Cortex-M0 (59 DMIPS, 142 CoreMark)
* 36 KB SRAM + 128 KB Flash
* 1x 12bit 16ch SAR ADC (2.5 MSPS)
* 4x USART + 2x I2C + 2x SPI

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

可以使用[platform-stm32](https://github.com/OS-Q/platform-stm32)进行开发，支持Arduino等多种开发框架。

## [选型建议](https://github.com/SoCXin/STM32G070)

目前LQFP-64封装的[STM32G070RBT6](https://item.szlcsc.com/549618.html) 具有很高的性价比，相较 [STM32G030](https://github.com/SoCXin/STM32G030) 拥有更大的SRAM和更大的封装，同时能够兼容。


### 开源方案

* [STM32CubeG0](https://github.com/STMicroelectronics/STM32CubeG0)
* [Arduino_Core](https://github.com/stm32duino/Arduino_Core_STM32)
* [PikaPython](https://github.com/OS-Q/PikaPython)
* [rust API](https://github.com/stm32-rs/stm32g0xx-hal)
