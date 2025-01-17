# Kriti RIU map

## PM

| riu addr |  phy addr  |             name              |
|----------|------------|-------------------------------|
| 0x000100 | 0x1f000200 | PM_RIU_DBG                    |
| 0x000200 | 0x1f000400 | MENULOAD                      |
| 0x000300 | 0x1f000600 | GDMA                          |
| 0x000400 | 0x1f000800 | DDC                           |
| 0x000800 | 0x1f001000 | ISP                           |
| 0x0008C0 | 0x1f001180 | FSP                           |
| 0x0008E0 | 0x1f0011c0 | QSPI                          |
| 0x000E00 | 0x1f001c00 | PM_SLEEP                      |
| 0x001000 | 0x1f002000 | MCU                           |
| 0x001100 | 0x1f002200 | PM_CEC                        |
| 0x001200 | 0x1f002400 | PM_RTC                        |
| 0x001300 | 0x1f002600 | PM_RTC2                       |
| 0x001400 | 0x1f002800 | PM_SAR                        |
| 0x001500 | 0x1f002a00 | PM_AV_LNK                     |
| 0x001E00 | 0x1f003c00 | PM_TOP                        |
| 0x002000 | 0x1f004000 | EFUSE                         |
| 0x002B00 | 0x1f005600 | IRQ                           |
| 0x002B80 | 0x1f005700 | CACHE                         |
| 0x002BC0 | 0x1f005780 | XDMIU                         |
| 0x003000 | 0x1f006000 | WDT                           |
| 0x003020 | 0x1f006040 | TIMER0                        |
| 0x003040 | 0x1f006080 | TIMER1                        |
| 0x003100 | 0x1f006200 | SEC_KEY                       |
| 0x003800 | 0x1f007000 | DID_KEY                       |
| 0x003C00 | 0x1f007800 | REG_PIU_MISC_0                |
| 0x003D00 | 0x1f007a00 | IR (rc5/etc)                  |
| 0x003D80 | 0x1f007b00 | IR (nec/etc)                  |

## Non-PM

| riu addr |  phy addr  |             name              |
|----------|------------|-------------------------------|
| 0x100100 | 0x1f200200 | RIU_DBG                       |
| 0x100200 | 0x1f200400 | MSPI0                         |
| 0x100240 | 0x1f200480 | MSPI1                         |
| 0x100300 | 0x1f200600 | VD_MHEG5                      |
| 0x100500 | 0x1f200a00 | POR_STATUS                    |
| 0x100540 | 0x1f200a80 | INTR_CPUINT                   |
| 0x100580 | 0x1f200b00 | NORPF                         |
| 0x100600 | 0x1f200c00 | MIU2                          |
| 0x100700 | 0x1f200e00 | USB0                          |
| 0x100780 | 0x1f200f00 | USB1                          |
| 0x100900 | 0x1f201200 | BDMA                          |
| 0x100980 | 0x1f201300 | UART0                         |
| 0x100B00 | 0x1f201600 | CLKGEN0                       |
| 0x100C00 | 0x1f201800 | DSCRMB                        |
| 0x100D00 | 0x1f201a00 | UHC1                          |
| 0x100F00 | 0x1f201e00 | MHEG5                         |
| 0x101100 | 0x1f202200 | MVD                           |
| 0x101200 | 0x1f202400 | MIU                           |
| 0x101300 | 0x1f202600 | MVOPSUB?                      |
| 0x101400 | 0x1f202800 | MVOP                          |
| 0x101500 | 0x1f202a00 | TSP0                          |
| 0x101600 | 0x1f202c00 | TSP1                          |
| 0x101700 | 0x1f202e00 | JPD                           |
| 0x101800 | 0x1f203000 | SEMAPH                        |
| 0x101840 | 0x1f203080 | MAU0                          |
| 0x101860 | 0x1f2030c0 | MAU1                          |
| 0x101880 | 0x1f203100 | MIPS_WDT                      |
| 0x1018C0 | 0x1f203180 | ECBRIDGE                      |
| 0x101900 | 0x1f203200 | INTR_CTRL                     |
| 0x101A00 | 0x1f203400 | HDMI2                         |
| 0x101B00 | 0x1f203600 | HVD                           |
| 0x101C00 | 0x1f203800 | TSP2                          |
| 0x101D00 | 0x1f203a00 | MIPS                          |
| 0x101E00 | 0x1f203c00 | CHIP                          |
| 0x101F00 | 0x1f203e00 | GOP                           |
| 0x102000 | 0x1f204000 | EMAC0                         |
| 0x102100 | 0x1f204200 | EMAC1                         |
| 0x102200 | 0x1f204400 | EMAC2                         |
| 0x102300 | 0x1f204600 | EMAC3                         |
| 0x102400 | 0x1f204800 | UHC                           |
| 0x102500 | 0x1f204a00 | ADC_ATOP                      |
| 0x102600 | 0x1f204c00 | ADC_DTOP                      |
| 0x102700 | 0x1f204e00 | HDMI                          |
| 0x102800 | 0x1f205000 | GE0                           |
| 0x102900 | 0x1f205200 | STRLD                         |
| 0x102A00 | 0x1f205400 | CI                            |
| 0x102B00 | 0x1f205600 | MIIC1                         |
| 0x102B80 | 0x1f205700 | MIIC2                         |
| 0x102C00 | 0x1f205800 | MIIC3                         |
| 0x102D00 | 0x1f205a00 | LDM_DMA0                      |
| 0x102D80 | 0x1f205b00 | LDM_DMA1                      |
| 0x102E00 | 0x1f205c00 | SC0 (IP_MUX)                  |
| 0x102F00 | 0x1f205e00 | SC1 (XC)                      |
| 0x103000 | 0x1f206000 | SC2 (HDGEN)                   |
| 0x103100 | 0x1f206200 | SC3 (LPLL)                    |
| 0x103200 | 0x1f206400 | SC4 (MOD)                     |
| 0x103300 | 0x1f206600 | CLKGEN1                       |
| 0x103380 | 0x1f206700 | MAILBOX                       |
| 0x103420 | 0x1f206840 | MIIC **?!**                   |
| 0x103440 | 0x1f206880 | PCM                           |
| 0x103460 | 0x1f2068c0 | VDMCU51_IF                    |
| 0x103480 | 0x1f206900 | DMDMCU51_IF                   |
| 0x1034A0 | 0x1f206940 | PM?                           |
| 0x1034C0 | 0x1f206980 | URDMA                         |
| 0x103500 | 0x1f206a00 | AFEC                          |
| 0x103600 | 0x1f206c00 | COMB                          |
| 0x103700 | 0x1f206e00 | VBI                           |
| 0x103800 | 0x1f207000 | SCM                           |
| 0x103900 | 0x1f207200 | HKVDIF                        |
| 0x103980 | 0x1f207300 | PATGEN                        |
| 0x103A00 | 0x1f207400 | UTMI1                         |
| 0x103A80 | 0x1f207500 | UTMI                          |
| 0x103B00 | 0x1f207600 | VE0                           |
| 0x103C00 | 0x1f207800 | PIU_NONPM                     |
| 0x103E00 | 0x1f207c00 | VE1                           |
| 0x103F00 | 0x1f207e00 | VE2                           |
| 0x110400 | 0x1f220800 | MPIF                          |
| 0x110500 | 0x1f220a00 | DEMOD?                        |
| 0x110600 | 0x1f220c00 | UART1                         |
| 0x110640 | 0x1f220c80 | UART2?                        |
| 0x110680 | 0x1f220d00 | FUART                         |
| 0x110700 | 0x1f220e00 | GE1                           |
| 0x110900 | 0x1f221200 | DVI_ATOP                      |
| 0x110A00 | 0x1f221400 | DVI_DTOP                      |
| 0x110A80 | 0x1f221500 | DVIEQ                         |
| 0x110AC0 | 0x1f221580 | HDCP                          |
| 0x110B00 | 0x1f221600 | NR_HSD?                       |
| 0x110C00 | 0x1f221800 | ANA_MISC                      |
| 0x110D00 | 0x1f221a00 | MIU_ATOP                      |
| 0x110D80 | 0x1f221b00 | MIU1_ATOP                     |
| 0x110E00 | 0x1f221c00 | NR?                           |
| 0x110F00 | 0x1f221e00 | DI?                           |
| 0x111000 | 0x1f222000 | MFE0?                         |
| 0x111100 | 0x1f222200 | MFE1?                         |
| 0x111200 | 0x1f222400 | ADC_DTOPB                     |
| 0x111300 | 0x1f222600 | NFIE0                         |
| 0x111400 | 0x1f222800 | NFIE1                         |
| 0x111500 | 0x1f222a00 | NFIE2                         |
| 0x111600 | 0x1f222c00 | ON                            |
| 0x111F00 | 0x1f223e00 | CLKGEN_DMD                    |
| 0x112000 | 0x1f224000 | DEMOD0                        |
| 0x112100 | 0x1f224200 | DEMOD1                        |
| 0x112200 | 0x1f224400 | DEMOD2                        |
| 0x112300 | 0x1f224600 | DEMOD3                        |
| 0x112400 | 0x1f224800 | DEMOD4                        |
| 0x112500 | 0x1f224a00 | DEMOD5                        |
| 0x112600 | 0x1f224c00 | DEMOD6                        |
| 0x112700 | 0x1f224e00 | DEMOD7                        |
| 0x112800 | 0x1f225000 | DMD_ANA_MISC                  |
| 0x112900 | 0x1f225200 | AUR20?                        |
| 0x112A00 | 0x1f225400 | VIVALDI0                      |
| 0x112B00 | 0x1f225600 | VIVALDI1                      |
| 0x112C00 | 0x1f225800 | VIVALDI2                      |
| 0x112D00 | 0x1f225a00 | VIVALDI3                      |
| 0x112E00 | 0x1f225c00 | VIVALDI4                      |
| 0x112F00 | 0x1f225e00 | VIVALDI5                      |
| 0x113000 | 0x1f226000 | AUR21?                        |
| 0x113100 | 0x1f226200 | AUR22?                        |
| 0x113200 | 0x1f226400 | DVI_ATOP1                     |
| 0x113300 | 0x1f226600 | DVI_DTOP1                     |
| 0x113380 | 0x1f226700 | DVIEQ1                        |
| 0x1133C0 | 0x1f226780 | HDCP1                         |
| 0x113400 | 0x1f226800 | DVI_ATOP2                     |
| 0x113500 | 0x1f226a00 | DVI_DTOP2                     |
| 0x113580 | 0x1f226b00 | DVIEQ2                        |
| 0x1135C0 | 0x1f226b80 | HDCP2                         |
| 0x113600 | 0x1f226c00 | DVI_PS                        |
| 0x113700 | 0x1f226e00 | DVI_DTOP3                     |
| 0x113780 | 0x1f226f00 | DVIEQ3                        |
| 0x1137C0 | 0x1f226f80 | HDCP3                         |
| 0x113C00 | 0x1f227800 | DSCRMB2                       |
| 0x120200 | 0x1f240400 | GOP4G_0                       |
| 0x120300 | 0x1f240600 | GOP4G_1                       |
| 0x120400 | 0x1f240800 | GOP4G_ST                      |
| 0x120500 | 0x1f240a00 | GOP2G_0                       |
| 0x120600 | 0x1f240c00 | GOP2G_1                       |
| 0x120700 | 0x1f240e00 | GOP2G_ST                      |
| 0x120800 | 0x1f241000 | GOP1G_0                       |
| 0x120A00 | 0x1f241400 | GOP1G_1                       |
| 0x120B00 | 0x1f241600 | GOP1G_ST                      |
| 0x120C00 | 0x1f241800 | GOP1GX_0                      |
| 0x120D00 | 0x1f241a00 | GOP1GX_1                      |
| 0x120E00 | 0x1f241c00 | GOP1GX_ST                     |
| 0x120F00 | 0x1f241e00 | GOPD                          |
| 0x121000 | 0x1f242000 | SPARE0                        |
| 0x121100 | 0x1f242200 | SPARE1                        |
| 0x121800 | 0x1f243000 | ALBANY0                       |
| 0x121900 | 0x1f243200 | ALBANY1                       |
| 0x130000 | 0x1f260000 | MSC                           |
