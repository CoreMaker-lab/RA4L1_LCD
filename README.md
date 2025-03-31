# Overview
- **Name**: RA4L1_LCD-V1.0
- **MCU**: R7FA4L1BD4CFP#BA0
- **IDE**: E2STUDIO

  


# Contact Information

- **Name**: Billy
- **交流群**: 925643491
- **Email**: a845656974@outlook.com
- **Phone**: +86 15622736378
- **CSDN Blog**: [Blog](https://blog.csdn.net/xinzuofang)
- **Video**: [Video](https://space.bilibili.com/3546563710290070)




# Buy Link
[https://shop192352884.taobao.com/](https://shop192352884.taobao.com/)

 
# Image

![image](https://github.com/user-attachments/assets/03191f8c-c783-42d1-a307-3027c67dd9f5)

![image](https://github.com/user-attachments/assets/2dda4386-2eca-4d25-89f6-fc1545a6ea0d)

![image](https://github.com/user-attachments/assets/e62236d2-e69f-4f58-b73f-aa7a56766a78)

![image](https://github.com/user-attachments/assets/034435cb-9ab3-4831-9ca8-921815f058a4)

![image](https://github.com/user-attachments/assets/0358b431-deab-491d-a769-9c139471cca9)

![image](https://github.com/user-attachments/assets/61d40c1c-bf8a-4553-b2fc-38f3cf96e67c)

![image](https://github.com/user-attachments/assets/1207e8e3-2026-47ff-b7a0-4bf57e9b34c7)


# Project Introduction

- **RA4L1_LCD_Project1**:RA4L1驱动LCD屏幕(1)----配置LCD
- **CSDN Blog**:[https://coremaker.blog.csdn.net/article/details/146589863](https://coremaker.blog.csdn.net/article/details/146589863)
- **Video**:[https://www.bilibili.com/video/BV1JuoUYnE2R/](https://www.bilibili.com/video/BV1JuoUYnE2R/)

液晶显示（LCD）是嵌入式系统中常见的人机交互方式，广泛应用于工业控制、智能家电、医疗设备和消费电子产品。Renesas RA4L1 微控制器（MCU）内置 Segment LCD Controller (SLCDC)，可直接驱动 静态、1/2、1/3、1/4 Bias 的段式 LCD 显示屏，无需额外的 LCD 驱动芯片。这种集成方案不仅降低了硬件成本，还简化了设计。
Renesas RA4L1 的 SLCDC 模块提供了一种高效、低功耗、低成本的 LCD 显示方案。通过 FSP 提供的 r_slcdc 驱动，开发者可以快速初始化 LCD，轻松控制显示内容。在实际项目中，合理配置 COM/SEG 引脚、优化时钟和对比度设置，可以进一步提升 LCD 显示效果。

Liquid Crystal Display (LCD) is a common human-machine interface in embedded systems, widely used in industrial control, smart appliances, medical devices, and consumer electronics. The Renesas RA4L1 microcontroller (MCU) features a built-in Segment LCD Controller (SLCDC) that can directly drive static, 1/2, 1/3, and 1/4 bias segment LCD panels, eliminating the need for an external LCD driver chip. This integrated solution not only reduces hardware cost but also simplifies system design.

The SLCDC module of the RA4L1 provides an efficient, low-power, and cost-effective LCD display solution. With the r_slcdc driver provided by the FSP (Flexible Software Package), developers can quickly initialize the LCD and easily control display content. In real-world applications, proper configuration of COM/SEG pins, as well as optimization of clock settings and contrast, can further enhance LCD display performance.


- **RA4L1_LCD_Project2**:RA4L1驱动LCD屏幕(2)----驱动LCD点亮
- **CSDN Blog**:[https://coremaker.blog.csdn.net/article/details/146590286](https://coremaker.blog.csdn.net/article/details/146590286)
- **Video**:[https://www.bilibili.com/video/BV1VHoUYGECR/](https://www.bilibili.com/video/BV1VHoUYGECR/)

本文旨在介绍如何使用瑞萨 RA4L1 系列单片机的 SLCDC（Segment LCD Controller）模块，驱动段式 LCD 屏幕实现字符或图案的点亮显示。通过分析 LCD 屏幕的 COM/SEG 引脚分布关系，结合 FSP（中的 SLCDC 驱动 API（如 R_SLCDC_Write() 和 R_SLCDC_Modify()），实现对单个或多个数码管笔段的精确控制。文中以实际硬件为例，展示如何点亮指定数码管（如显示数字“1”或“3”），并解释段寄存器设置、位图控制方法以及显示时序，为后续 LCD 显示开发和调试提供参考。

This article aims to demonstrate how to use the SLCDC (Segment LCD Controller) module of the Renesas RA4L1 series microcontroller to drive a segment LCD screen for displaying characters or patterns.

By analyzing the COM/SEG pin mapping of the LCD panel and leveraging the SLCDC driver APIs provided in the FSP (such as R_SLCDC_Write() and R_SLCDC_Modify()), developers can achieve precise control over individual or multiple segments of a digital display.

Using actual hardware as an example, the article illustrates how to light up specific digits (e.g., displaying the number “1” or “3”) and explains segment register settings, bitmap control methods, and display timing. This serves as a practical reference for subsequent LCD display development and debugging.


















