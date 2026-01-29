# OnePlus 15R / Ace 6T (Macan) Development

This repository serves as a centralized hub for information regarding the **OnePlus 15R** (Global) and **OnePlus Ace 6T** (China). The ultimate goal is the development of a functional Device Tree and the subsequent porting of **LineageOS**.

## Device Specifications

| Feature | Details |
| :--- | :--- |
| **Codename** | `Macan` |
| **China Model** | OnePlus Ace 6T (`PLR110`) |
| **India Model** | OnePlus 15R (`CPH2767`) |
| **NA Model** | OnePlus 15R (`CPH2771`) |
| **Global/EU Model** | OnePlus 15R (`CPH2769`) |
| **Platform** | Qualcomm Snapdragon 8 Gen 5 (SM8845) `Canoe` |

| Variant | ro.product.device |
| :--- | :--- |
| **PLR110** |  OP6117L1 |

> [!IMPORTANT]  
> **SoC Note:** This device uses the **SM8845** platform. Please note that this is the Snapdragon 8 Gen 5, **not** the 8 Elite Gen 5 SM8850.\n
>  The codename for the platform is `canoe` and is shared by both platforms, this should make working on the devices easier as fixes should be the same.
> [Detailed SoC Product Brief](https://www.qualcomm.com/content/dam/qcomm-martech/dm-assets/documents/Product-Brief-Snapdragon-8-Gen-5.pdf)

---

## 🛠 Source Code (OnePlusOSS)

Official kernel sources released by OnePlus for the SM8845 platform:

*   **Kernel Source:** [android_kernel_oneplus_sm8845](https://github.com/OnePlusOSS/android_kernel_oneplus_sm8845)
*   **Kernel Modules & Device Tree:** [android_kernel_modules_and_devicetree_oneplus_sm8845](https://github.com/OnePlusOSS/android_kernel_modules_and_devicetree_oneplus_sm8845)
*   **Kernel Common:** [android_kernel_common_oneplus_sm8845](https://github.com/OnePlusOSS/android_kernel_common_oneplus_sm8845)

---

## 🏗 Development Resources

### Recovery
*   **OrangeFox Recovery (Alpha):** [android_device_oneplus_macan-orangefox](https://github.com/koaaN/android_device_oneplus_macan-orangefox/tree/main)  
    *Note: This is the first recovery build and still requires extensive testing.*

### Firmware & Community
*   **Firmware Downloads:** [danielspringer.at](https://danielspringer.at/)
*   **Discussion:** [OnePlus 15R XDA Forum](https://xdaforums.com/f/oneplus-15r.12990/)

---
