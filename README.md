# **微星B660M迫击炮WiFi黑苹果EFI**

## **配置**

| 组件          | 型号                          |
| ------------- | ----------------------------- |
| **CPU**       | **12th-i5-12400**             |
| **主板**      | **微星B660M迫击炮Wi-Fi DDR4** |
| **显卡**      | **5600XT**            |
| **网卡**      | **AX211**                     |
| **OC版本**    | **0.8.6**                     |
| **MacOS版本** | **MacOS Venture 13.0**        |
| **机箱**      | **傻瓜超人K88青春版**         |

**根据大佬[lyq1996](https://github.com/lyq1996/MSI-B660M-MORTAR-WIFI_Hackintosh_12700_6800XT)发布的EFI做了稍微修改：**

- **重新定制了USB(只适用与K88青春版)，前面板usb3.0接口、type-C接口、后面主板四个usb2.0接口、USB3.0接口、type-C接口**
- **注入WIFI和蓝牙驱动**
- **由于i5-12400没有E-Core,删除CpuTopologyRebuild.kext**
