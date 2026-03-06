# edk2-sprd_sharkl
UEFI compatible with Unisoc (SharklE) chip

Unisoc is another name for sprd.

### Warning: If the initialization gap of uboot is too large, this project may not be suitable for your device

SharkLE layout SoC:
| SoC                      | Board                          | Instruction Set| Support             |
| ------------------------ | ------------------------------ | -------------- | ------------------- |
| SC9820E / SL8521E        | sp9820e_1h10/sl8521_1h10/ll    | ARMv8/32_mode  | Missing source code |
| SC9832E / SL8541E        | sp9832e_1h10/sl8541e_1h10      | ARMv8          | Boot Uefi Shell     |
| W377                     | uws6137_1h10                   | ARMv8/32_mode  | Missing source code |
| W377E                    | uws6137_1h10_64b               | ARMv8          | No equipment        |
