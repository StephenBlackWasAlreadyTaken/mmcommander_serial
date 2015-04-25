                                      1 ;--------------------------------------------------------
                                      2 ; File Created by SDCC : free open source ANSI-C Compiler
                                      3 ; Version 3.4.0 #8981 (Apr  5 2014) (MINGW64)
                                      4 ; This file was generated Sat Apr 25 00:05:12 2015
                                      5 ;--------------------------------------------------------
                                      6 	.module hal_mcu
                                      7 	.optsdcc -mmcs51 --model-large
                                      8 	
                                      9 ;--------------------------------------------------------
                                     10 ; Public variables in this module
                                     11 ;--------------------------------------------------------
                                     12 	.globl _clockSetMainSrc
                                     13 	.globl _MODE
                                     14 	.globl _RE
                                     15 	.globl _SLAVE
                                     16 	.globl _FE
                                     17 	.globl _ERR
                                     18 	.globl _RX_BYTE
                                     19 	.globl _TX_BYTE
                                     20 	.globl _ACTIVE
                                     21 	.globl _B_7
                                     22 	.globl _B_6
                                     23 	.globl _B_5
                                     24 	.globl _B_4
                                     25 	.globl _B_3
                                     26 	.globl _B_2
                                     27 	.globl _B_1
                                     28 	.globl _B_0
                                     29 	.globl _WDTIF
                                     30 	.globl _P1IF
                                     31 	.globl _UTX1IF
                                     32 	.globl _UTX0IF
                                     33 	.globl _P2IF
                                     34 	.globl _ACC_7
                                     35 	.globl _ACC_6
                                     36 	.globl _ACC_5
                                     37 	.globl _ACC_4
                                     38 	.globl _ACC_3
                                     39 	.globl _ACC_2
                                     40 	.globl _ACC_1
                                     41 	.globl _ACC_0
                                     42 	.globl _OVFIM
                                     43 	.globl _T4CH1IF
                                     44 	.globl _T4CH0IF
                                     45 	.globl _T4OVFIF
                                     46 	.globl _T3CH1IF
                                     47 	.globl _T3CH0IF
                                     48 	.globl _T3OVFIF
                                     49 	.globl _CY
                                     50 	.globl _AC
                                     51 	.globl _F0
                                     52 	.globl _RS1
                                     53 	.globl _RS0
                                     54 	.globl _OV
                                     55 	.globl _F1
                                     56 	.globl _P
                                     57 	.globl _STIF
                                     58 	.globl _P0IF
                                     59 	.globl _T4IF
                                     60 	.globl _T3IF
                                     61 	.globl _T2IF
                                     62 	.globl _T1IF
                                     63 	.globl _DMAIF
                                     64 	.globl _P0IE
                                     65 	.globl _T4IE
                                     66 	.globl _T3IE
                                     67 	.globl _T2IE
                                     68 	.globl _T1IE
                                     69 	.globl _DMAIE
                                     70 	.globl _EA
                                     71 	.globl _STIE
                                     72 	.globl _ENCIE
                                     73 	.globl _URX1IE
                                     74 	.globl _URX0IE
                                     75 	.globl _ADCIE
                                     76 	.globl _RFTXRXIE
                                     77 	.globl _P2_7
                                     78 	.globl _P2_6
                                     79 	.globl _P2_5
                                     80 	.globl _P2_4
                                     81 	.globl _P2_3
                                     82 	.globl _P2_2
                                     83 	.globl _P2_1
                                     84 	.globl _P2_0
                                     85 	.globl _ENCIF_1
                                     86 	.globl _ENCIF_0
                                     87 	.globl _P1_7
                                     88 	.globl _P1_6
                                     89 	.globl _P1_5
                                     90 	.globl _P1_4
                                     91 	.globl _P1_3
                                     92 	.globl _P1_2
                                     93 	.globl _P1_1
                                     94 	.globl _P1_0
                                     95 	.globl _URX1IF
                                     96 	.globl _ADCIF
                                     97 	.globl _URX0IF
                                     98 	.globl _IT1
                                     99 	.globl _RFTXRXIF
                                    100 	.globl _IT0
                                    101 	.globl _P0_7
                                    102 	.globl _P0_6
                                    103 	.globl _P0_5
                                    104 	.globl _P0_4
                                    105 	.globl _P0_3
                                    106 	.globl _P0_2
                                    107 	.globl _P0_1
                                    108 	.globl _P0_0
                                    109 	.globl _P2DIR
                                    110 	.globl _P1DIR
                                    111 	.globl _P0DIR
                                    112 	.globl _U1GCR
                                    113 	.globl _U1UCR
                                    114 	.globl _U1BAUD
                                    115 	.globl _U1DBUF
                                    116 	.globl _U1CSR
                                    117 	.globl _P2INP
                                    118 	.globl _P1INP
                                    119 	.globl _P2SEL
                                    120 	.globl _P1SEL
                                    121 	.globl _P0SEL
                                    122 	.globl _ADCCFG
                                    123 	.globl _PERCFG
                                    124 	.globl _B
                                    125 	.globl _T4CC1
                                    126 	.globl _T4CCTL1
                                    127 	.globl _T4CC0
                                    128 	.globl _T4CCTL0
                                    129 	.globl _T4CTL
                                    130 	.globl _T4CNT
                                    131 	.globl _RFIF
                                    132 	.globl _IRCON2
                                    133 	.globl _T1CCTL2
                                    134 	.globl _T1CCTL1
                                    135 	.globl _T1CCTL0
                                    136 	.globl _T1CTL
                                    137 	.globl _T1CNTH
                                    138 	.globl _T1CNTL
                                    139 	.globl _RFST
                                    140 	.globl _ACC
                                    141 	.globl _T1CC2H
                                    142 	.globl _T1CC2L
                                    143 	.globl _T1CC1H
                                    144 	.globl _T1CC1L
                                    145 	.globl _T1CC0H
                                    146 	.globl _T1CC0L
                                    147 	.globl _RFD
                                    148 	.globl _TIMIF
                                    149 	.globl _DMAREQ
                                    150 	.globl _DMAARM
                                    151 	.globl _DMA0CFGH
                                    152 	.globl _DMA0CFGL
                                    153 	.globl _DMA1CFGH
                                    154 	.globl _DMA1CFGL
                                    155 	.globl _DMAIRQ
                                    156 	.globl _PSW
                                    157 	.globl _T3CC1
                                    158 	.globl _T3CCTL1
                                    159 	.globl _T3CC0
                                    160 	.globl _T3CCTL0
                                    161 	.globl _T3CTL
                                    162 	.globl _T3CNT
                                    163 	.globl _WDCTL
                                    164 	.globl __SFRC8
                                    165 	.globl _MEMCTR
                                    166 	.globl _CLKCON
                                    167 	.globl _U0GCR
                                    168 	.globl _U0UCR
                                    169 	.globl __SFRC3
                                    170 	.globl _U0BAUD
                                    171 	.globl _U0DBUF
                                    172 	.globl _IRCON
                                    173 	.globl __SFRBF
                                    174 	.globl _SLEEP
                                    175 	.globl _RNDH
                                    176 	.globl _RNDL
                                    177 	.globl _ADCH
                                    178 	.globl _ADCL
                                    179 	.globl _IP1
                                    180 	.globl _IEN1
                                    181 	.globl __SFRB7
                                    182 	.globl _ADCCON3
                                    183 	.globl _ADCCON2
                                    184 	.globl _ADCCON1
                                    185 	.globl _ENCCS
                                    186 	.globl _ENCDO
                                    187 	.globl _ENCDI
                                    188 	.globl __SFRB0
                                    189 	.globl _FWDATA
                                    190 	.globl _FCTL
                                    191 	.globl _FADDRH
                                    192 	.globl _FADDRL
                                    193 	.globl _FWT
                                    194 	.globl __SFRAA
                                    195 	.globl _IP0
                                    196 	.globl _IEN0
                                    197 	.globl __SFRA7
                                    198 	.globl _WORTIME1
                                    199 	.globl _WORTIME0
                                    200 	.globl _WOREVT1
                                    201 	.globl _WOREVT0
                                    202 	.globl _WORCTRL
                                    203 	.globl _WORIRQ
                                    204 	.globl _P2
                                    205 	.globl __SFR9F
                                    206 	.globl _T2CTL
                                    207 	.globl _T2PR
                                    208 	.globl _T2CT
                                    209 	.globl _S1CON
                                    210 	.globl _IEN2
                                    211 	.globl __SFR99
                                    212 	.globl _S0CON
                                    213 	.globl __SFR97
                                    214 	.globl __SFR96
                                    215 	.globl __SFR95
                                    216 	.globl __SFR94
                                    217 	.globl __XPAGE
                                    218 	.globl _MPAGE
                                    219 	.globl _DPS
                                    220 	.globl _RFIM
                                    221 	.globl _P1
                                    222 	.globl _P0INP
                                    223 	.globl __SFR8E
                                    224 	.globl _P1IEN
                                    225 	.globl _PICTL
                                    226 	.globl _P2IFG
                                    227 	.globl _P1IFG
                                    228 	.globl _P0IFG
                                    229 	.globl _TCON
                                    230 	.globl _PCON
                                    231 	.globl _U0CSR
                                    232 	.globl _DPH1
                                    233 	.globl _DPL1
                                    234 	.globl _DPH0
                                    235 	.globl _DPL0
                                    236 	.globl _SP
                                    237 	.globl _P0
                                    238 	.globl _X_P2DIR
                                    239 	.globl _X_P1DIR
                                    240 	.globl _X_P0DIR
                                    241 	.globl _X_U1GCR
                                    242 	.globl _X_U1UCR
                                    243 	.globl _X_U1BAUD
                                    244 	.globl _X_U1DBUF
                                    245 	.globl _X_U1CSR
                                    246 	.globl _X_P2INP
                                    247 	.globl _X_P1INP
                                    248 	.globl _X_P2SEL
                                    249 	.globl _X_P1SEL
                                    250 	.globl _X_P0SEL
                                    251 	.globl _X_ADCCFG
                                    252 	.globl _X_PERCFG
                                    253 	.globl __NA_B
                                    254 	.globl _X_T4CC1
                                    255 	.globl _X_T4CCTL1
                                    256 	.globl _X_T4CC0
                                    257 	.globl _X_T4CCTL0
                                    258 	.globl _X_T4CTL
                                    259 	.globl _X_T4CNT
                                    260 	.globl _X_RFIF
                                    261 	.globl __NA_IRCON2
                                    262 	.globl _X_T1CCTL2
                                    263 	.globl _X_T1CCTL1
                                    264 	.globl _X_T1CCTL0
                                    265 	.globl _X_T1CTL
                                    266 	.globl _X_T1CNTH
                                    267 	.globl _X_T1CNTL
                                    268 	.globl _X_RFST
                                    269 	.globl __NA_ACC
                                    270 	.globl _X_T1CC2H
                                    271 	.globl _X_T1CC2L
                                    272 	.globl _X_T1CC1H
                                    273 	.globl _X_T1CC1L
                                    274 	.globl _X_T1CC0H
                                    275 	.globl _X_T1CC0L
                                    276 	.globl _X_RFD
                                    277 	.globl _X_TIMIF
                                    278 	.globl _X_DMAREQ
                                    279 	.globl _X_DMAARM
                                    280 	.globl _X_DMA0CFGH
                                    281 	.globl _X_DMA0CFGL
                                    282 	.globl _X_DMA1CFGH
                                    283 	.globl _X_DMA1CFGL
                                    284 	.globl _X_DMAIRQ
                                    285 	.globl __NA_PSW
                                    286 	.globl _X_T3CC1
                                    287 	.globl _X_T3CCTL1
                                    288 	.globl _X_T3CC0
                                    289 	.globl _X_T3CCTL0
                                    290 	.globl _X_T3CTL
                                    291 	.globl _X_T3CNT
                                    292 	.globl _X_WDCTL
                                    293 	.globl __X_SFRC8
                                    294 	.globl _X_MEMCTR
                                    295 	.globl _X_CLKCON
                                    296 	.globl _X_U0GCR
                                    297 	.globl _X_U0UCR
                                    298 	.globl __X_SFRC3
                                    299 	.globl _X_U0BAUD
                                    300 	.globl _X_U0DBUF
                                    301 	.globl __NA_IRCON
                                    302 	.globl __X_SFRBF
                                    303 	.globl _X_SLEEP
                                    304 	.globl _X_RNDH
                                    305 	.globl _X_RNDL
                                    306 	.globl _X_ADCH
                                    307 	.globl _X_ADCL
                                    308 	.globl __NA_IP1
                                    309 	.globl __NA_IEN1
                                    310 	.globl __X_SFRB7
                                    311 	.globl _X_ADCCON3
                                    312 	.globl _X_ADCCON2
                                    313 	.globl _X_ADCCON1
                                    314 	.globl _X_ENCCS
                                    315 	.globl _X_ENCDO
                                    316 	.globl _X_ENCDI
                                    317 	.globl __X_SFRB0
                                    318 	.globl _X_FWDATA
                                    319 	.globl _X_FCTL
                                    320 	.globl _X_FADDRH
                                    321 	.globl _X_FADDRL
                                    322 	.globl _X_FWT
                                    323 	.globl __X_SFRAA
                                    324 	.globl __NA_IP0
                                    325 	.globl __NA_IEN0
                                    326 	.globl __X_SFRA7
                                    327 	.globl _X_WORTIME1
                                    328 	.globl _X_WORTIME0
                                    329 	.globl _X_WOREVT1
                                    330 	.globl _X_WOREVT0
                                    331 	.globl _X_WORCTRL
                                    332 	.globl _X_WORIRQ
                                    333 	.globl __NA_P2
                                    334 	.globl __X_SFR9F
                                    335 	.globl _X_T2CTL
                                    336 	.globl _X_T2PR
                                    337 	.globl _X_T2CT
                                    338 	.globl __NA_S1CON
                                    339 	.globl __NA_IEN2
                                    340 	.globl __X_SFR99
                                    341 	.globl __NA_S0CON
                                    342 	.globl __X_SFR97
                                    343 	.globl __X_SFR96
                                    344 	.globl __X_SFR95
                                    345 	.globl __X_SFR94
                                    346 	.globl _X_MPAGE
                                    347 	.globl __NA_DPS
                                    348 	.globl _X_RFIM
                                    349 	.globl __NA_P1
                                    350 	.globl _X_P0INP
                                    351 	.globl __X_SFR8E
                                    352 	.globl _X_P1IEN
                                    353 	.globl _X_PICTL
                                    354 	.globl _X_P2IFG
                                    355 	.globl _X_P1IFG
                                    356 	.globl _X_P0IFG
                                    357 	.globl __NA_TCON
                                    358 	.globl __NA_PCON
                                    359 	.globl _X_U0CSR
                                    360 	.globl __NA_DPH1
                                    361 	.globl __NA_DPL1
                                    362 	.globl __NA_DPH0
                                    363 	.globl __NA_DPL0
                                    364 	.globl __NA_SP
                                    365 	.globl __NA_P0
                                    366 	.globl _I2SCLKF2
                                    367 	.globl _I2SCLKF1
                                    368 	.globl _I2SCLKF0
                                    369 	.globl _I2SSTAT
                                    370 	.globl _I2SWCNT
                                    371 	.globl _I2SDATH
                                    372 	.globl _I2SDATL
                                    373 	.globl _I2SCFG1
                                    374 	.globl _I2SCFG0
                                    375 	.globl _VCO_VC_DAC
                                    376 	.globl _PKTSTATUS
                                    377 	.globl _MARCSTATE
                                    378 	.globl _RSSI
                                    379 	.globl _LQI
                                    380 	.globl _FREQEST
                                    381 	.globl _VERSION
                                    382 	.globl _PARTNUM
                                    383 	.globl __XREGDF35
                                    384 	.globl __XREGDF34
                                    385 	.globl __XREGDF33
                                    386 	.globl __XREGDF32
                                    387 	.globl _IOCFG0
                                    388 	.globl _IOCFG1
                                    389 	.globl _IOCFG2
                                    390 	.globl _PA_TABLE0
                                    391 	.globl _PA_TABLE1
                                    392 	.globl _PA_TABLE2
                                    393 	.globl _PA_TABLE3
                                    394 	.globl _PA_TABLE4
                                    395 	.globl _PA_TABLE5
                                    396 	.globl _PA_TABLE6
                                    397 	.globl _PA_TABLE7
                                    398 	.globl __XREGDF26
                                    399 	.globl _TEST0
                                    400 	.globl _TEST1
                                    401 	.globl _TEST2
                                    402 	.globl __XREGDF22
                                    403 	.globl __XREGDF21
                                    404 	.globl __XREGDF20
                                    405 	.globl _FSCAL0
                                    406 	.globl _FSCAL1
                                    407 	.globl _FSCAL2
                                    408 	.globl _FSCAL3
                                    409 	.globl _FREND0
                                    410 	.globl _FREND1
                                    411 	.globl _AGCCTRL0
                                    412 	.globl _AGCCTRL1
                                    413 	.globl _AGCCTRL2
                                    414 	.globl _BSCFG
                                    415 	.globl _FOCCFG
                                    416 	.globl _MCSM0
                                    417 	.globl _MCSM1
                                    418 	.globl _MCSM2
                                    419 	.globl _DEVIATN
                                    420 	.globl _MDMCFG0
                                    421 	.globl _MDMCFG1
                                    422 	.globl _MDMCFG2
                                    423 	.globl _MDMCFG3
                                    424 	.globl _MDMCFG4
                                    425 	.globl _FREQ0
                                    426 	.globl _FREQ1
                                    427 	.globl _FREQ2
                                    428 	.globl _FSCTRL0
                                    429 	.globl _FSCTRL1
                                    430 	.globl _CHANNR
                                    431 	.globl _ADDR
                                    432 	.globl _PKTCTRL0
                                    433 	.globl _PKTCTRL1
                                    434 	.globl _PKTLEN
                                    435 	.globl _SYNC0
                                    436 	.globl _SYNC1
                                    437 	.globl _MDMCTRL0H
                                    438 	.globl _halMcuInit
                                    439 	.globl _halMcuWaitUs
                                    440 	.globl _halMcuWaitMs
                                    441 	.globl _halMcuSetLowPowerMode
                                    442 	.globl _halMcuReset
                                    443 ;--------------------------------------------------------
                                    444 ; special function registers
                                    445 ;--------------------------------------------------------
                                    446 	.area RSEG    (ABS,DATA)
      000000                        447 	.org 0x0000
                           000080   448 G$P0$0$0 == 0x0080
                           000080   449 _P0	=	0x0080
                           000081   450 G$SP$0$0 == 0x0081
                           000081   451 _SP	=	0x0081
                           000082   452 G$DPL0$0$0 == 0x0082
                           000082   453 _DPL0	=	0x0082
                           000083   454 G$DPH0$0$0 == 0x0083
                           000083   455 _DPH0	=	0x0083
                           000084   456 G$DPL1$0$0 == 0x0084
                           000084   457 _DPL1	=	0x0084
                           000085   458 G$DPH1$0$0 == 0x0085
                           000085   459 _DPH1	=	0x0085
                           000086   460 G$U0CSR$0$0 == 0x0086
                           000086   461 _U0CSR	=	0x0086
                           000087   462 G$PCON$0$0 == 0x0087
                           000087   463 _PCON	=	0x0087
                           000088   464 G$TCON$0$0 == 0x0088
                           000088   465 _TCON	=	0x0088
                           000089   466 G$P0IFG$0$0 == 0x0089
                           000089   467 _P0IFG	=	0x0089
                           00008A   468 G$P1IFG$0$0 == 0x008a
                           00008A   469 _P1IFG	=	0x008a
                           00008B   470 G$P2IFG$0$0 == 0x008b
                           00008B   471 _P2IFG	=	0x008b
                           00008C   472 G$PICTL$0$0 == 0x008c
                           00008C   473 _PICTL	=	0x008c
                           00008D   474 G$P1IEN$0$0 == 0x008d
                           00008D   475 _P1IEN	=	0x008d
                           00008E   476 G$_SFR8E$0$0 == 0x008e
                           00008E   477 __SFR8E	=	0x008e
                           00008F   478 G$P0INP$0$0 == 0x008f
                           00008F   479 _P0INP	=	0x008f
                           000090   480 G$P1$0$0 == 0x0090
                           000090   481 _P1	=	0x0090
                           000091   482 G$RFIM$0$0 == 0x0091
                           000091   483 _RFIM	=	0x0091
                           000092   484 G$DPS$0$0 == 0x0092
                           000092   485 _DPS	=	0x0092
                           000093   486 G$MPAGE$0$0 == 0x0093
                           000093   487 _MPAGE	=	0x0093
                           000093   488 G$_XPAGE$0$0 == 0x0093
                           000093   489 __XPAGE	=	0x0093
                           000094   490 G$_SFR94$0$0 == 0x0094
                           000094   491 __SFR94	=	0x0094
                           000095   492 G$_SFR95$0$0 == 0x0095
                           000095   493 __SFR95	=	0x0095
                           000096   494 G$_SFR96$0$0 == 0x0096
                           000096   495 __SFR96	=	0x0096
                           000097   496 G$_SFR97$0$0 == 0x0097
                           000097   497 __SFR97	=	0x0097
                           000098   498 G$S0CON$0$0 == 0x0098
                           000098   499 _S0CON	=	0x0098
                           000099   500 G$_SFR99$0$0 == 0x0099
                           000099   501 __SFR99	=	0x0099
                           00009A   502 G$IEN2$0$0 == 0x009a
                           00009A   503 _IEN2	=	0x009a
                           00009B   504 G$S1CON$0$0 == 0x009b
                           00009B   505 _S1CON	=	0x009b
                           00009C   506 G$T2CT$0$0 == 0x009c
                           00009C   507 _T2CT	=	0x009c
                           00009D   508 G$T2PR$0$0 == 0x009d
                           00009D   509 _T2PR	=	0x009d
                           00009E   510 G$T2CTL$0$0 == 0x009e
                           00009E   511 _T2CTL	=	0x009e
                           00009F   512 G$_SFR9F$0$0 == 0x009f
                           00009F   513 __SFR9F	=	0x009f
                           0000A0   514 G$P2$0$0 == 0x00a0
                           0000A0   515 _P2	=	0x00a0
                           0000A1   516 G$WORIRQ$0$0 == 0x00a1
                           0000A1   517 _WORIRQ	=	0x00a1
                           0000A2   518 G$WORCTRL$0$0 == 0x00a2
                           0000A2   519 _WORCTRL	=	0x00a2
                           0000A3   520 G$WOREVT0$0$0 == 0x00a3
                           0000A3   521 _WOREVT0	=	0x00a3
                           0000A4   522 G$WOREVT1$0$0 == 0x00a4
                           0000A4   523 _WOREVT1	=	0x00a4
                           0000A5   524 G$WORTIME0$0$0 == 0x00a5
                           0000A5   525 _WORTIME0	=	0x00a5
                           0000A6   526 G$WORTIME1$0$0 == 0x00a6
                           0000A6   527 _WORTIME1	=	0x00a6
                           0000A7   528 G$_SFRA7$0$0 == 0x00a7
                           0000A7   529 __SFRA7	=	0x00a7
                           0000A8   530 G$IEN0$0$0 == 0x00a8
                           0000A8   531 _IEN0	=	0x00a8
                           0000A9   532 G$IP0$0$0 == 0x00a9
                           0000A9   533 _IP0	=	0x00a9
                           0000AA   534 G$_SFRAA$0$0 == 0x00aa
                           0000AA   535 __SFRAA	=	0x00aa
                           0000AB   536 G$FWT$0$0 == 0x00ab
                           0000AB   537 _FWT	=	0x00ab
                           0000AC   538 G$FADDRL$0$0 == 0x00ac
                           0000AC   539 _FADDRL	=	0x00ac
                           0000AD   540 G$FADDRH$0$0 == 0x00ad
                           0000AD   541 _FADDRH	=	0x00ad
                           0000AE   542 G$FCTL$0$0 == 0x00ae
                           0000AE   543 _FCTL	=	0x00ae
                           0000AF   544 G$FWDATA$0$0 == 0x00af
                           0000AF   545 _FWDATA	=	0x00af
                           0000B0   546 G$_SFRB0$0$0 == 0x00b0
                           0000B0   547 __SFRB0	=	0x00b0
                           0000B1   548 G$ENCDI$0$0 == 0x00b1
                           0000B1   549 _ENCDI	=	0x00b1
                           0000B2   550 G$ENCDO$0$0 == 0x00b2
                           0000B2   551 _ENCDO	=	0x00b2
                           0000B3   552 G$ENCCS$0$0 == 0x00b3
                           0000B3   553 _ENCCS	=	0x00b3
                           0000B4   554 G$ADCCON1$0$0 == 0x00b4
                           0000B4   555 _ADCCON1	=	0x00b4
                           0000B5   556 G$ADCCON2$0$0 == 0x00b5
                           0000B5   557 _ADCCON2	=	0x00b5
                           0000B6   558 G$ADCCON3$0$0 == 0x00b6
                           0000B6   559 _ADCCON3	=	0x00b6
                           0000B7   560 G$_SFRB7$0$0 == 0x00b7
                           0000B7   561 __SFRB7	=	0x00b7
                           0000B8   562 G$IEN1$0$0 == 0x00b8
                           0000B8   563 _IEN1	=	0x00b8
                           0000B9   564 G$IP1$0$0 == 0x00b9
                           0000B9   565 _IP1	=	0x00b9
                           0000BA   566 G$ADCL$0$0 == 0x00ba
                           0000BA   567 _ADCL	=	0x00ba
                           0000BB   568 G$ADCH$0$0 == 0x00bb
                           0000BB   569 _ADCH	=	0x00bb
                           0000BC   570 G$RNDL$0$0 == 0x00bc
                           0000BC   571 _RNDL	=	0x00bc
                           0000BD   572 G$RNDH$0$0 == 0x00bd
                           0000BD   573 _RNDH	=	0x00bd
                           0000BE   574 G$SLEEP$0$0 == 0x00be
                           0000BE   575 _SLEEP	=	0x00be
                           0000BF   576 G$_SFRBF$0$0 == 0x00bf
                           0000BF   577 __SFRBF	=	0x00bf
                           0000C0   578 G$IRCON$0$0 == 0x00c0
                           0000C0   579 _IRCON	=	0x00c0
                           0000C1   580 G$U0DBUF$0$0 == 0x00c1
                           0000C1   581 _U0DBUF	=	0x00c1
                           0000C2   582 G$U0BAUD$0$0 == 0x00c2
                           0000C2   583 _U0BAUD	=	0x00c2
                           0000C3   584 G$_SFRC3$0$0 == 0x00c3
                           0000C3   585 __SFRC3	=	0x00c3
                           0000C4   586 G$U0UCR$0$0 == 0x00c4
                           0000C4   587 _U0UCR	=	0x00c4
                           0000C5   588 G$U0GCR$0$0 == 0x00c5
                           0000C5   589 _U0GCR	=	0x00c5
                           0000C6   590 G$CLKCON$0$0 == 0x00c6
                           0000C6   591 _CLKCON	=	0x00c6
                           0000C7   592 G$MEMCTR$0$0 == 0x00c7
                           0000C7   593 _MEMCTR	=	0x00c7
                           0000C8   594 G$_SFRC8$0$0 == 0x00c8
                           0000C8   595 __SFRC8	=	0x00c8
                           0000C9   596 G$WDCTL$0$0 == 0x00c9
                           0000C9   597 _WDCTL	=	0x00c9
                           0000CA   598 G$T3CNT$0$0 == 0x00ca
                           0000CA   599 _T3CNT	=	0x00ca
                           0000CB   600 G$T3CTL$0$0 == 0x00cb
                           0000CB   601 _T3CTL	=	0x00cb
                           0000CC   602 G$T3CCTL0$0$0 == 0x00cc
                           0000CC   603 _T3CCTL0	=	0x00cc
                           0000CD   604 G$T3CC0$0$0 == 0x00cd
                           0000CD   605 _T3CC0	=	0x00cd
                           0000CE   606 G$T3CCTL1$0$0 == 0x00ce
                           0000CE   607 _T3CCTL1	=	0x00ce
                           0000CF   608 G$T3CC1$0$0 == 0x00cf
                           0000CF   609 _T3CC1	=	0x00cf
                           0000D0   610 G$PSW$0$0 == 0x00d0
                           0000D0   611 _PSW	=	0x00d0
                           0000D1   612 G$DMAIRQ$0$0 == 0x00d1
                           0000D1   613 _DMAIRQ	=	0x00d1
                           0000D2   614 G$DMA1CFGL$0$0 == 0x00d2
                           0000D2   615 _DMA1CFGL	=	0x00d2
                           0000D3   616 G$DMA1CFGH$0$0 == 0x00d3
                           0000D3   617 _DMA1CFGH	=	0x00d3
                           0000D4   618 G$DMA0CFGL$0$0 == 0x00d4
                           0000D4   619 _DMA0CFGL	=	0x00d4
                           0000D5   620 G$DMA0CFGH$0$0 == 0x00d5
                           0000D5   621 _DMA0CFGH	=	0x00d5
                           0000D6   622 G$DMAARM$0$0 == 0x00d6
                           0000D6   623 _DMAARM	=	0x00d6
                           0000D7   624 G$DMAREQ$0$0 == 0x00d7
                           0000D7   625 _DMAREQ	=	0x00d7
                           0000D8   626 G$TIMIF$0$0 == 0x00d8
                           0000D8   627 _TIMIF	=	0x00d8
                           0000D9   628 G$RFD$0$0 == 0x00d9
                           0000D9   629 _RFD	=	0x00d9
                           0000DA   630 G$T1CC0L$0$0 == 0x00da
                           0000DA   631 _T1CC0L	=	0x00da
                           0000DB   632 G$T1CC0H$0$0 == 0x00db
                           0000DB   633 _T1CC0H	=	0x00db
                           0000DC   634 G$T1CC1L$0$0 == 0x00dc
                           0000DC   635 _T1CC1L	=	0x00dc
                           0000DD   636 G$T1CC1H$0$0 == 0x00dd
                           0000DD   637 _T1CC1H	=	0x00dd
                           0000DE   638 G$T1CC2L$0$0 == 0x00de
                           0000DE   639 _T1CC2L	=	0x00de
                           0000DF   640 G$T1CC2H$0$0 == 0x00df
                           0000DF   641 _T1CC2H	=	0x00df
                           0000E0   642 G$ACC$0$0 == 0x00e0
                           0000E0   643 _ACC	=	0x00e0
                           0000E1   644 G$RFST$0$0 == 0x00e1
                           0000E1   645 _RFST	=	0x00e1
                           0000E2   646 G$T1CNTL$0$0 == 0x00e2
                           0000E2   647 _T1CNTL	=	0x00e2
                           0000E3   648 G$T1CNTH$0$0 == 0x00e3
                           0000E3   649 _T1CNTH	=	0x00e3
                           0000E4   650 G$T1CTL$0$0 == 0x00e4
                           0000E4   651 _T1CTL	=	0x00e4
                           0000E5   652 G$T1CCTL0$0$0 == 0x00e5
                           0000E5   653 _T1CCTL0	=	0x00e5
                           0000E6   654 G$T1CCTL1$0$0 == 0x00e6
                           0000E6   655 _T1CCTL1	=	0x00e6
                           0000E7   656 G$T1CCTL2$0$0 == 0x00e7
                           0000E7   657 _T1CCTL2	=	0x00e7
                           0000E8   658 G$IRCON2$0$0 == 0x00e8
                           0000E8   659 _IRCON2	=	0x00e8
                           0000E9   660 G$RFIF$0$0 == 0x00e9
                           0000E9   661 _RFIF	=	0x00e9
                           0000EA   662 G$T4CNT$0$0 == 0x00ea
                           0000EA   663 _T4CNT	=	0x00ea
                           0000EB   664 G$T4CTL$0$0 == 0x00eb
                           0000EB   665 _T4CTL	=	0x00eb
                           0000EC   666 G$T4CCTL0$0$0 == 0x00ec
                           0000EC   667 _T4CCTL0	=	0x00ec
                           0000ED   668 G$T4CC0$0$0 == 0x00ed
                           0000ED   669 _T4CC0	=	0x00ed
                           0000EE   670 G$T4CCTL1$0$0 == 0x00ee
                           0000EE   671 _T4CCTL1	=	0x00ee
                           0000EF   672 G$T4CC1$0$0 == 0x00ef
                           0000EF   673 _T4CC1	=	0x00ef
                           0000F0   674 G$B$0$0 == 0x00f0
                           0000F0   675 _B	=	0x00f0
                           0000F1   676 G$PERCFG$0$0 == 0x00f1
                           0000F1   677 _PERCFG	=	0x00f1
                           0000F2   678 G$ADCCFG$0$0 == 0x00f2
                           0000F2   679 _ADCCFG	=	0x00f2
                           0000F3   680 G$P0SEL$0$0 == 0x00f3
                           0000F3   681 _P0SEL	=	0x00f3
                           0000F4   682 G$P1SEL$0$0 == 0x00f4
                           0000F4   683 _P1SEL	=	0x00f4
                           0000F5   684 G$P2SEL$0$0 == 0x00f5
                           0000F5   685 _P2SEL	=	0x00f5
                           0000F6   686 G$P1INP$0$0 == 0x00f6
                           0000F6   687 _P1INP	=	0x00f6
                           0000F7   688 G$P2INP$0$0 == 0x00f7
                           0000F7   689 _P2INP	=	0x00f7
                           0000F8   690 G$U1CSR$0$0 == 0x00f8
                           0000F8   691 _U1CSR	=	0x00f8
                           0000F9   692 G$U1DBUF$0$0 == 0x00f9
                           0000F9   693 _U1DBUF	=	0x00f9
                           0000FA   694 G$U1BAUD$0$0 == 0x00fa
                           0000FA   695 _U1BAUD	=	0x00fa
                           0000FB   696 G$U1UCR$0$0 == 0x00fb
                           0000FB   697 _U1UCR	=	0x00fb
                           0000FC   698 G$U1GCR$0$0 == 0x00fc
                           0000FC   699 _U1GCR	=	0x00fc
                           0000FD   700 G$P0DIR$0$0 == 0x00fd
                           0000FD   701 _P0DIR	=	0x00fd
                           0000FE   702 G$P1DIR$0$0 == 0x00fe
                           0000FE   703 _P1DIR	=	0x00fe
                           0000FF   704 G$P2DIR$0$0 == 0x00ff
                           0000FF   705 _P2DIR	=	0x00ff
                                    706 ;--------------------------------------------------------
                                    707 ; special function bits
                                    708 ;--------------------------------------------------------
                                    709 	.area RSEG    (ABS,DATA)
      000000                        710 	.org 0x0000
                           000080   711 G$P0_0$0$0 == 0x0080
                           000080   712 _P0_0	=	0x0080
                           000081   713 G$P0_1$0$0 == 0x0081
                           000081   714 _P0_1	=	0x0081
                           000082   715 G$P0_2$0$0 == 0x0082
                           000082   716 _P0_2	=	0x0082
                           000083   717 G$P0_3$0$0 == 0x0083
                           000083   718 _P0_3	=	0x0083
                           000084   719 G$P0_4$0$0 == 0x0084
                           000084   720 _P0_4	=	0x0084
                           000085   721 G$P0_5$0$0 == 0x0085
                           000085   722 _P0_5	=	0x0085
                           000086   723 G$P0_6$0$0 == 0x0086
                           000086   724 _P0_6	=	0x0086
                           000087   725 G$P0_7$0$0 == 0x0087
                           000087   726 _P0_7	=	0x0087
                           000088   727 G$IT0$0$0 == 0x0088
                           000088   728 _IT0	=	0x0088
                           000089   729 G$RFTXRXIF$0$0 == 0x0089
                           000089   730 _RFTXRXIF	=	0x0089
                           00008A   731 G$IT1$0$0 == 0x008a
                           00008A   732 _IT1	=	0x008a
                           00008B   733 G$URX0IF$0$0 == 0x008b
                           00008B   734 _URX0IF	=	0x008b
                           00008D   735 G$ADCIF$0$0 == 0x008d
                           00008D   736 _ADCIF	=	0x008d
                           00008F   737 G$URX1IF$0$0 == 0x008f
                           00008F   738 _URX1IF	=	0x008f
                           000090   739 G$P1_0$0$0 == 0x0090
                           000090   740 _P1_0	=	0x0090
                           000091   741 G$P1_1$0$0 == 0x0091
                           000091   742 _P1_1	=	0x0091
                           000092   743 G$P1_2$0$0 == 0x0092
                           000092   744 _P1_2	=	0x0092
                           000093   745 G$P1_3$0$0 == 0x0093
                           000093   746 _P1_3	=	0x0093
                           000094   747 G$P1_4$0$0 == 0x0094
                           000094   748 _P1_4	=	0x0094
                           000095   749 G$P1_5$0$0 == 0x0095
                           000095   750 _P1_5	=	0x0095
                           000096   751 G$P1_6$0$0 == 0x0096
                           000096   752 _P1_6	=	0x0096
                           000097   753 G$P1_7$0$0 == 0x0097
                           000097   754 _P1_7	=	0x0097
                           000098   755 G$ENCIF_0$0$0 == 0x0098
                           000098   756 _ENCIF_0	=	0x0098
                           000099   757 G$ENCIF_1$0$0 == 0x0099
                           000099   758 _ENCIF_1	=	0x0099
                           0000A0   759 G$P2_0$0$0 == 0x00a0
                           0000A0   760 _P2_0	=	0x00a0
                           0000A1   761 G$P2_1$0$0 == 0x00a1
                           0000A1   762 _P2_1	=	0x00a1
                           0000A2   763 G$P2_2$0$0 == 0x00a2
                           0000A2   764 _P2_2	=	0x00a2
                           0000A3   765 G$P2_3$0$0 == 0x00a3
                           0000A3   766 _P2_3	=	0x00a3
                           0000A4   767 G$P2_4$0$0 == 0x00a4
                           0000A4   768 _P2_4	=	0x00a4
                           0000A5   769 G$P2_5$0$0 == 0x00a5
                           0000A5   770 _P2_5	=	0x00a5
                           0000A6   771 G$P2_6$0$0 == 0x00a6
                           0000A6   772 _P2_6	=	0x00a6
                           0000A7   773 G$P2_7$0$0 == 0x00a7
                           0000A7   774 _P2_7	=	0x00a7
                           0000A8   775 G$RFTXRXIE$0$0 == 0x00a8
                           0000A8   776 _RFTXRXIE	=	0x00a8
                           0000A9   777 G$ADCIE$0$0 == 0x00a9
                           0000A9   778 _ADCIE	=	0x00a9
                           0000AA   779 G$URX0IE$0$0 == 0x00aa
                           0000AA   780 _URX0IE	=	0x00aa
                           0000AB   781 G$URX1IE$0$0 == 0x00ab
                           0000AB   782 _URX1IE	=	0x00ab
                           0000AC   783 G$ENCIE$0$0 == 0x00ac
                           0000AC   784 _ENCIE	=	0x00ac
                           0000AD   785 G$STIE$0$0 == 0x00ad
                           0000AD   786 _STIE	=	0x00ad
                           0000AF   787 G$EA$0$0 == 0x00af
                           0000AF   788 _EA	=	0x00af
                           0000B8   789 G$DMAIE$0$0 == 0x00b8
                           0000B8   790 _DMAIE	=	0x00b8
                           0000B9   791 G$T1IE$0$0 == 0x00b9
                           0000B9   792 _T1IE	=	0x00b9
                           0000BA   793 G$T2IE$0$0 == 0x00ba
                           0000BA   794 _T2IE	=	0x00ba
                           0000BB   795 G$T3IE$0$0 == 0x00bb
                           0000BB   796 _T3IE	=	0x00bb
                           0000BC   797 G$T4IE$0$0 == 0x00bc
                           0000BC   798 _T4IE	=	0x00bc
                           0000BD   799 G$P0IE$0$0 == 0x00bd
                           0000BD   800 _P0IE	=	0x00bd
                           0000C0   801 G$DMAIF$0$0 == 0x00c0
                           0000C0   802 _DMAIF	=	0x00c0
                           0000C1   803 G$T1IF$0$0 == 0x00c1
                           0000C1   804 _T1IF	=	0x00c1
                           0000C2   805 G$T2IF$0$0 == 0x00c2
                           0000C2   806 _T2IF	=	0x00c2
                           0000C3   807 G$T3IF$0$0 == 0x00c3
                           0000C3   808 _T3IF	=	0x00c3
                           0000C4   809 G$T4IF$0$0 == 0x00c4
                           0000C4   810 _T4IF	=	0x00c4
                           0000C5   811 G$P0IF$0$0 == 0x00c5
                           0000C5   812 _P0IF	=	0x00c5
                           0000C7   813 G$STIF$0$0 == 0x00c7
                           0000C7   814 _STIF	=	0x00c7
                           0000D0   815 G$P$0$0 == 0x00d0
                           0000D0   816 _P	=	0x00d0
                           0000D1   817 G$F1$0$0 == 0x00d1
                           0000D1   818 _F1	=	0x00d1
                           0000D2   819 G$OV$0$0 == 0x00d2
                           0000D2   820 _OV	=	0x00d2
                           0000D3   821 G$RS0$0$0 == 0x00d3
                           0000D3   822 _RS0	=	0x00d3
                           0000D4   823 G$RS1$0$0 == 0x00d4
                           0000D4   824 _RS1	=	0x00d4
                           0000D5   825 G$F0$0$0 == 0x00d5
                           0000D5   826 _F0	=	0x00d5
                           0000D6   827 G$AC$0$0 == 0x00d6
                           0000D6   828 _AC	=	0x00d6
                           0000D7   829 G$CY$0$0 == 0x00d7
                           0000D7   830 _CY	=	0x00d7
                           0000D8   831 G$T3OVFIF$0$0 == 0x00d8
                           0000D8   832 _T3OVFIF	=	0x00d8
                           0000D9   833 G$T3CH0IF$0$0 == 0x00d9
                           0000D9   834 _T3CH0IF	=	0x00d9
                           0000DA   835 G$T3CH1IF$0$0 == 0x00da
                           0000DA   836 _T3CH1IF	=	0x00da
                           0000DB   837 G$T4OVFIF$0$0 == 0x00db
                           0000DB   838 _T4OVFIF	=	0x00db
                           0000DC   839 G$T4CH0IF$0$0 == 0x00dc
                           0000DC   840 _T4CH0IF	=	0x00dc
                           0000DD   841 G$T4CH1IF$0$0 == 0x00dd
                           0000DD   842 _T4CH1IF	=	0x00dd
                           0000DE   843 G$OVFIM$0$0 == 0x00de
                           0000DE   844 _OVFIM	=	0x00de
                           0000E0   845 G$ACC_0$0$0 == 0x00e0
                           0000E0   846 _ACC_0	=	0x00e0
                           0000E1   847 G$ACC_1$0$0 == 0x00e1
                           0000E1   848 _ACC_1	=	0x00e1
                           0000E2   849 G$ACC_2$0$0 == 0x00e2
                           0000E2   850 _ACC_2	=	0x00e2
                           0000E3   851 G$ACC_3$0$0 == 0x00e3
                           0000E3   852 _ACC_3	=	0x00e3
                           0000E4   853 G$ACC_4$0$0 == 0x00e4
                           0000E4   854 _ACC_4	=	0x00e4
                           0000E5   855 G$ACC_5$0$0 == 0x00e5
                           0000E5   856 _ACC_5	=	0x00e5
                           0000E6   857 G$ACC_6$0$0 == 0x00e6
                           0000E6   858 _ACC_6	=	0x00e6
                           0000E7   859 G$ACC_7$0$0 == 0x00e7
                           0000E7   860 _ACC_7	=	0x00e7
                           0000E8   861 G$P2IF$0$0 == 0x00e8
                           0000E8   862 _P2IF	=	0x00e8
                           0000E9   863 G$UTX0IF$0$0 == 0x00e9
                           0000E9   864 _UTX0IF	=	0x00e9
                           0000EA   865 G$UTX1IF$0$0 == 0x00ea
                           0000EA   866 _UTX1IF	=	0x00ea
                           0000EB   867 G$P1IF$0$0 == 0x00eb
                           0000EB   868 _P1IF	=	0x00eb
                           0000EC   869 G$WDTIF$0$0 == 0x00ec
                           0000EC   870 _WDTIF	=	0x00ec
                           0000F0   871 G$B_0$0$0 == 0x00f0
                           0000F0   872 _B_0	=	0x00f0
                           0000F1   873 G$B_1$0$0 == 0x00f1
                           0000F1   874 _B_1	=	0x00f1
                           0000F2   875 G$B_2$0$0 == 0x00f2
                           0000F2   876 _B_2	=	0x00f2
                           0000F3   877 G$B_3$0$0 == 0x00f3
                           0000F3   878 _B_3	=	0x00f3
                           0000F4   879 G$B_4$0$0 == 0x00f4
                           0000F4   880 _B_4	=	0x00f4
                           0000F5   881 G$B_5$0$0 == 0x00f5
                           0000F5   882 _B_5	=	0x00f5
                           0000F6   883 G$B_6$0$0 == 0x00f6
                           0000F6   884 _B_6	=	0x00f6
                           0000F7   885 G$B_7$0$0 == 0x00f7
                           0000F7   886 _B_7	=	0x00f7
                           0000F8   887 G$ACTIVE$0$0 == 0x00f8
                           0000F8   888 _ACTIVE	=	0x00f8
                           0000F9   889 G$TX_BYTE$0$0 == 0x00f9
                           0000F9   890 _TX_BYTE	=	0x00f9
                           0000FA   891 G$RX_BYTE$0$0 == 0x00fa
                           0000FA   892 _RX_BYTE	=	0x00fa
                           0000FB   893 G$ERR$0$0 == 0x00fb
                           0000FB   894 _ERR	=	0x00fb
                           0000FC   895 G$FE$0$0 == 0x00fc
                           0000FC   896 _FE	=	0x00fc
                           0000FD   897 G$SLAVE$0$0 == 0x00fd
                           0000FD   898 _SLAVE	=	0x00fd
                           0000FE   899 G$RE$0$0 == 0x00fe
                           0000FE   900 _RE	=	0x00fe
                           0000FF   901 G$MODE$0$0 == 0x00ff
                           0000FF   902 _MODE	=	0x00ff
                                    903 ;--------------------------------------------------------
                                    904 ; overlayable register banks
                                    905 ;--------------------------------------------------------
                                    906 	.area REG_BANK_0	(REL,OVR,DATA)
      000000                        907 	.ds 8
                                    908 ;--------------------------------------------------------
                                    909 ; internal ram data
                                    910 ;--------------------------------------------------------
                                    911 	.area DSEG    (DATA)
                                    912 ;--------------------------------------------------------
                                    913 ; overlayable items in internal ram 
                                    914 ;--------------------------------------------------------
                                    915 ;--------------------------------------------------------
                                    916 ; indirectly addressable internal ram data
                                    917 ;--------------------------------------------------------
                                    918 	.area ISEG    (DATA)
                                    919 ;--------------------------------------------------------
                                    920 ; absolute internal ram data
                                    921 ;--------------------------------------------------------
                                    922 	.area IABS    (ABS,DATA)
                                    923 	.area IABS    (ABS,DATA)
                                    924 ;--------------------------------------------------------
                                    925 ; bit data
                                    926 ;--------------------------------------------------------
                                    927 	.area BSEG    (BIT)
                                    928 ;--------------------------------------------------------
                                    929 ; paged external ram data
                                    930 ;--------------------------------------------------------
                                    931 	.area PSEG    (PAG,XDATA)
                                    932 ;--------------------------------------------------------
                                    933 ; external ram data
                                    934 ;--------------------------------------------------------
                                    935 	.area XSEG    (XDATA)
                           00DF02   936 G$MDMCTRL0H$0$0 == 0xdf02
                           00DF02   937 _MDMCTRL0H	=	0xdf02
                           00DF00   938 G$SYNC1$0$0 == 0xdf00
                           00DF00   939 _SYNC1	=	0xdf00
                           00DF01   940 G$SYNC0$0$0 == 0xdf01
                           00DF01   941 _SYNC0	=	0xdf01
                           00DF02   942 G$PKTLEN$0$0 == 0xdf02
                           00DF02   943 _PKTLEN	=	0xdf02
                           00DF03   944 G$PKTCTRL1$0$0 == 0xdf03
                           00DF03   945 _PKTCTRL1	=	0xdf03
                           00DF04   946 G$PKTCTRL0$0$0 == 0xdf04
                           00DF04   947 _PKTCTRL0	=	0xdf04
                           00DF05   948 G$ADDR$0$0 == 0xdf05
                           00DF05   949 _ADDR	=	0xdf05
                           00DF06   950 G$CHANNR$0$0 == 0xdf06
                           00DF06   951 _CHANNR	=	0xdf06
                           00DF07   952 G$FSCTRL1$0$0 == 0xdf07
                           00DF07   953 _FSCTRL1	=	0xdf07
                           00DF08   954 G$FSCTRL0$0$0 == 0xdf08
                           00DF08   955 _FSCTRL0	=	0xdf08
                           00DF09   956 G$FREQ2$0$0 == 0xdf09
                           00DF09   957 _FREQ2	=	0xdf09
                           00DF0A   958 G$FREQ1$0$0 == 0xdf0a
                           00DF0A   959 _FREQ1	=	0xdf0a
                           00DF0B   960 G$FREQ0$0$0 == 0xdf0b
                           00DF0B   961 _FREQ0	=	0xdf0b
                           00DF0C   962 G$MDMCFG4$0$0 == 0xdf0c
                           00DF0C   963 _MDMCFG4	=	0xdf0c
                           00DF0D   964 G$MDMCFG3$0$0 == 0xdf0d
                           00DF0D   965 _MDMCFG3	=	0xdf0d
                           00DF0E   966 G$MDMCFG2$0$0 == 0xdf0e
                           00DF0E   967 _MDMCFG2	=	0xdf0e
                           00DF0F   968 G$MDMCFG1$0$0 == 0xdf0f
                           00DF0F   969 _MDMCFG1	=	0xdf0f
                           00DF10   970 G$MDMCFG0$0$0 == 0xdf10
                           00DF10   971 _MDMCFG0	=	0xdf10
                           00DF11   972 G$DEVIATN$0$0 == 0xdf11
                           00DF11   973 _DEVIATN	=	0xdf11
                           00DF12   974 G$MCSM2$0$0 == 0xdf12
                           00DF12   975 _MCSM2	=	0xdf12
                           00DF13   976 G$MCSM1$0$0 == 0xdf13
                           00DF13   977 _MCSM1	=	0xdf13
                           00DF14   978 G$MCSM0$0$0 == 0xdf14
                           00DF14   979 _MCSM0	=	0xdf14
                           00DF15   980 G$FOCCFG$0$0 == 0xdf15
                           00DF15   981 _FOCCFG	=	0xdf15
                           00DF16   982 G$BSCFG$0$0 == 0xdf16
                           00DF16   983 _BSCFG	=	0xdf16
                           00DF17   984 G$AGCCTRL2$0$0 == 0xdf17
                           00DF17   985 _AGCCTRL2	=	0xdf17
                           00DF18   986 G$AGCCTRL1$0$0 == 0xdf18
                           00DF18   987 _AGCCTRL1	=	0xdf18
                           00DF19   988 G$AGCCTRL0$0$0 == 0xdf19
                           00DF19   989 _AGCCTRL0	=	0xdf19
                           00DF1A   990 G$FREND1$0$0 == 0xdf1a
                           00DF1A   991 _FREND1	=	0xdf1a
                           00DF1B   992 G$FREND0$0$0 == 0xdf1b
                           00DF1B   993 _FREND0	=	0xdf1b
                           00DF1C   994 G$FSCAL3$0$0 == 0xdf1c
                           00DF1C   995 _FSCAL3	=	0xdf1c
                           00DF1D   996 G$FSCAL2$0$0 == 0xdf1d
                           00DF1D   997 _FSCAL2	=	0xdf1d
                           00DF1E   998 G$FSCAL1$0$0 == 0xdf1e
                           00DF1E   999 _FSCAL1	=	0xdf1e
                           00DF1F  1000 G$FSCAL0$0$0 == 0xdf1f
                           00DF1F  1001 _FSCAL0	=	0xdf1f
                           00DF20  1002 G$_XREGDF20$0$0 == 0xdf20
                           00DF20  1003 __XREGDF20	=	0xdf20
                           00DF21  1004 G$_XREGDF21$0$0 == 0xdf21
                           00DF21  1005 __XREGDF21	=	0xdf21
                           00DF22  1006 G$_XREGDF22$0$0 == 0xdf22
                           00DF22  1007 __XREGDF22	=	0xdf22
                           00DF23  1008 G$TEST2$0$0 == 0xdf23
                           00DF23  1009 _TEST2	=	0xdf23
                           00DF24  1010 G$TEST1$0$0 == 0xdf24
                           00DF24  1011 _TEST1	=	0xdf24
                           00DF25  1012 G$TEST0$0$0 == 0xdf25
                           00DF25  1013 _TEST0	=	0xdf25
                           00DF26  1014 G$_XREGDF26$0$0 == 0xdf26
                           00DF26  1015 __XREGDF26	=	0xdf26
                           00DF27  1016 G$PA_TABLE7$0$0 == 0xdf27
                           00DF27  1017 _PA_TABLE7	=	0xdf27
                           00DF28  1018 G$PA_TABLE6$0$0 == 0xdf28
                           00DF28  1019 _PA_TABLE6	=	0xdf28
                           00DF29  1020 G$PA_TABLE5$0$0 == 0xdf29
                           00DF29  1021 _PA_TABLE5	=	0xdf29
                           00DF2A  1022 G$PA_TABLE4$0$0 == 0xdf2a
                           00DF2A  1023 _PA_TABLE4	=	0xdf2a
                           00DF2B  1024 G$PA_TABLE3$0$0 == 0xdf2b
                           00DF2B  1025 _PA_TABLE3	=	0xdf2b
                           00DF2C  1026 G$PA_TABLE2$0$0 == 0xdf2c
                           00DF2C  1027 _PA_TABLE2	=	0xdf2c
                           00DF2D  1028 G$PA_TABLE1$0$0 == 0xdf2d
                           00DF2D  1029 _PA_TABLE1	=	0xdf2d
                           00DF2E  1030 G$PA_TABLE0$0$0 == 0xdf2e
                           00DF2E  1031 _PA_TABLE0	=	0xdf2e
                           00DF2F  1032 G$IOCFG2$0$0 == 0xdf2f
                           00DF2F  1033 _IOCFG2	=	0xdf2f
                           00DF30  1034 G$IOCFG1$0$0 == 0xdf30
                           00DF30  1035 _IOCFG1	=	0xdf30
                           00DF31  1036 G$IOCFG0$0$0 == 0xdf31
                           00DF31  1037 _IOCFG0	=	0xdf31
                           00DF32  1038 G$_XREGDF32$0$0 == 0xdf32
                           00DF32  1039 __XREGDF32	=	0xdf32
                           00DF33  1040 G$_XREGDF33$0$0 == 0xdf33
                           00DF33  1041 __XREGDF33	=	0xdf33
                           00DF34  1042 G$_XREGDF34$0$0 == 0xdf34
                           00DF34  1043 __XREGDF34	=	0xdf34
                           00DF35  1044 G$_XREGDF35$0$0 == 0xdf35
                           00DF35  1045 __XREGDF35	=	0xdf35
                           00DF36  1046 G$PARTNUM$0$0 == 0xdf36
                           00DF36  1047 _PARTNUM	=	0xdf36
                           00DF37  1048 G$VERSION$0$0 == 0xdf37
                           00DF37  1049 _VERSION	=	0xdf37
                           00DF38  1050 G$FREQEST$0$0 == 0xdf38
                           00DF38  1051 _FREQEST	=	0xdf38
                           00DF39  1052 G$LQI$0$0 == 0xdf39
                           00DF39  1053 _LQI	=	0xdf39
                           00DF3A  1054 G$RSSI$0$0 == 0xdf3a
                           00DF3A  1055 _RSSI	=	0xdf3a
                           00DF3B  1056 G$MARCSTATE$0$0 == 0xdf3b
                           00DF3B  1057 _MARCSTATE	=	0xdf3b
                           00DF3C  1058 G$PKTSTATUS$0$0 == 0xdf3c
                           00DF3C  1059 _PKTSTATUS	=	0xdf3c
                           00DF3D  1060 G$VCO_VC_DAC$0$0 == 0xdf3d
                           00DF3D  1061 _VCO_VC_DAC	=	0xdf3d
                           00DF40  1062 G$I2SCFG0$0$0 == 0xdf40
                           00DF40  1063 _I2SCFG0	=	0xdf40
                           00DF41  1064 G$I2SCFG1$0$0 == 0xdf41
                           00DF41  1065 _I2SCFG1	=	0xdf41
                           00DF42  1066 G$I2SDATL$0$0 == 0xdf42
                           00DF42  1067 _I2SDATL	=	0xdf42
                           00DF43  1068 G$I2SDATH$0$0 == 0xdf43
                           00DF43  1069 _I2SDATH	=	0xdf43
                           00DF44  1070 G$I2SWCNT$0$0 == 0xdf44
                           00DF44  1071 _I2SWCNT	=	0xdf44
                           00DF45  1072 G$I2SSTAT$0$0 == 0xdf45
                           00DF45  1073 _I2SSTAT	=	0xdf45
                           00DF46  1074 G$I2SCLKF0$0$0 == 0xdf46
                           00DF46  1075 _I2SCLKF0	=	0xdf46
                           00DF47  1076 G$I2SCLKF1$0$0 == 0xdf47
                           00DF47  1077 _I2SCLKF1	=	0xdf47
                           00DF48  1078 G$I2SCLKF2$0$0 == 0xdf48
                           00DF48  1079 _I2SCLKF2	=	0xdf48
                           00DF80  1080 G$_NA_P0$0$0 == 0xdf80
                           00DF80  1081 __NA_P0	=	0xdf80
                           00DF81  1082 G$_NA_SP$0$0 == 0xdf81
                           00DF81  1083 __NA_SP	=	0xdf81
                           00DF82  1084 G$_NA_DPL0$0$0 == 0xdf82
                           00DF82  1085 __NA_DPL0	=	0xdf82
                           00DF83  1086 G$_NA_DPH0$0$0 == 0xdf83
                           00DF83  1087 __NA_DPH0	=	0xdf83
                           00DF84  1088 G$_NA_DPL1$0$0 == 0xdf84
                           00DF84  1089 __NA_DPL1	=	0xdf84
                           00DF85  1090 G$_NA_DPH1$0$0 == 0xdf85
                           00DF85  1091 __NA_DPH1	=	0xdf85
                           00DF86  1092 G$X_U0CSR$0$0 == 0xdf86
                           00DF86  1093 _X_U0CSR	=	0xdf86
                           00DF87  1094 G$_NA_PCON$0$0 == 0xdf87
                           00DF87  1095 __NA_PCON	=	0xdf87
                           00DF88  1096 G$_NA_TCON$0$0 == 0xdf88
                           00DF88  1097 __NA_TCON	=	0xdf88
                           00DF89  1098 G$X_P0IFG$0$0 == 0xdf89
                           00DF89  1099 _X_P0IFG	=	0xdf89
                           00DF8A  1100 G$X_P1IFG$0$0 == 0xdf8a
                           00DF8A  1101 _X_P1IFG	=	0xdf8a
                           00DF8B  1102 G$X_P2IFG$0$0 == 0xdf8b
                           00DF8B  1103 _X_P2IFG	=	0xdf8b
                           00DF8C  1104 G$X_PICTL$0$0 == 0xdf8c
                           00DF8C  1105 _X_PICTL	=	0xdf8c
                           00DF8D  1106 G$X_P1IEN$0$0 == 0xdf8d
                           00DF8D  1107 _X_P1IEN	=	0xdf8d
                           00DF8E  1108 G$_X_SFR8E$0$0 == 0xdf8e
                           00DF8E  1109 __X_SFR8E	=	0xdf8e
                           00DF8F  1110 G$X_P0INP$0$0 == 0xdf8f
                           00DF8F  1111 _X_P0INP	=	0xdf8f
                           00DF90  1112 G$_NA_P1$0$0 == 0xdf90
                           00DF90  1113 __NA_P1	=	0xdf90
                           00DF91  1114 G$X_RFIM$0$0 == 0xdf91
                           00DF91  1115 _X_RFIM	=	0xdf91
                           00DF92  1116 G$_NA_DPS$0$0 == 0xdf92
                           00DF92  1117 __NA_DPS	=	0xdf92
                           00DF93  1118 G$X_MPAGE$0$0 == 0xdf93
                           00DF93  1119 _X_MPAGE	=	0xdf93
                           00DF94  1120 G$_X_SFR94$0$0 == 0xdf94
                           00DF94  1121 __X_SFR94	=	0xdf94
                           00DF95  1122 G$_X_SFR95$0$0 == 0xdf95
                           00DF95  1123 __X_SFR95	=	0xdf95
                           00DF96  1124 G$_X_SFR96$0$0 == 0xdf96
                           00DF96  1125 __X_SFR96	=	0xdf96
                           00DF97  1126 G$_X_SFR97$0$0 == 0xdf97
                           00DF97  1127 __X_SFR97	=	0xdf97
                           00DF98  1128 G$_NA_S0CON$0$0 == 0xdf98
                           00DF98  1129 __NA_S0CON	=	0xdf98
                           00DF99  1130 G$_X_SFR99$0$0 == 0xdf99
                           00DF99  1131 __X_SFR99	=	0xdf99
                           00DF9A  1132 G$_NA_IEN2$0$0 == 0xdf9a
                           00DF9A  1133 __NA_IEN2	=	0xdf9a
                           00DF9B  1134 G$_NA_S1CON$0$0 == 0xdf9b
                           00DF9B  1135 __NA_S1CON	=	0xdf9b
                           00DF9C  1136 G$X_T2CT$0$0 == 0xdf9c
                           00DF9C  1137 _X_T2CT	=	0xdf9c
                           00DF9D  1138 G$X_T2PR$0$0 == 0xdf9d
                           00DF9D  1139 _X_T2PR	=	0xdf9d
                           00DF9E  1140 G$X_T2CTL$0$0 == 0xdf9e
                           00DF9E  1141 _X_T2CTL	=	0xdf9e
                           00DF9F  1142 G$_X_SFR9F$0$0 == 0xdf9f
                           00DF9F  1143 __X_SFR9F	=	0xdf9f
                           00DFA0  1144 G$_NA_P2$0$0 == 0xdfa0
                           00DFA0  1145 __NA_P2	=	0xdfa0
                           00DFA1  1146 G$X_WORIRQ$0$0 == 0xdfa1
                           00DFA1  1147 _X_WORIRQ	=	0xdfa1
                           00DFA2  1148 G$X_WORCTRL$0$0 == 0xdfa2
                           00DFA2  1149 _X_WORCTRL	=	0xdfa2
                           00DFA3  1150 G$X_WOREVT0$0$0 == 0xdfa3
                           00DFA3  1151 _X_WOREVT0	=	0xdfa3
                           00DFA4  1152 G$X_WOREVT1$0$0 == 0xdfa4
                           00DFA4  1153 _X_WOREVT1	=	0xdfa4
                           00DFA5  1154 G$X_WORTIME0$0$0 == 0xdfa5
                           00DFA5  1155 _X_WORTIME0	=	0xdfa5
                           00DFA6  1156 G$X_WORTIME1$0$0 == 0xdfa6
                           00DFA6  1157 _X_WORTIME1	=	0xdfa6
                           00DFA7  1158 G$_X_SFRA7$0$0 == 0xdfa7
                           00DFA7  1159 __X_SFRA7	=	0xdfa7
                           00DFA8  1160 G$_NA_IEN0$0$0 == 0xdfa8
                           00DFA8  1161 __NA_IEN0	=	0xdfa8
                           00DFA9  1162 G$_NA_IP0$0$0 == 0xdfa9
                           00DFA9  1163 __NA_IP0	=	0xdfa9
                           00DFAA  1164 G$_X_SFRAA$0$0 == 0xdfaa
                           00DFAA  1165 __X_SFRAA	=	0xdfaa
                           00DFAB  1166 G$X_FWT$0$0 == 0xdfab
                           00DFAB  1167 _X_FWT	=	0xdfab
                           00DFAC  1168 G$X_FADDRL$0$0 == 0xdfac
                           00DFAC  1169 _X_FADDRL	=	0xdfac
                           00DFAD  1170 G$X_FADDRH$0$0 == 0xdfad
                           00DFAD  1171 _X_FADDRH	=	0xdfad
                           00DFAE  1172 G$X_FCTL$0$0 == 0xdfae
                           00DFAE  1173 _X_FCTL	=	0xdfae
                           00DFAF  1174 G$X_FWDATA$0$0 == 0xdfaf
                           00DFAF  1175 _X_FWDATA	=	0xdfaf
                           00DFB0  1176 G$_X_SFRB0$0$0 == 0xdfb0
                           00DFB0  1177 __X_SFRB0	=	0xdfb0
                           00DFB1  1178 G$X_ENCDI$0$0 == 0xdfb1
                           00DFB1  1179 _X_ENCDI	=	0xdfb1
                           00DFB2  1180 G$X_ENCDO$0$0 == 0xdfb2
                           00DFB2  1181 _X_ENCDO	=	0xdfb2
                           00DFB3  1182 G$X_ENCCS$0$0 == 0xdfb3
                           00DFB3  1183 _X_ENCCS	=	0xdfb3
                           00DFB4  1184 G$X_ADCCON1$0$0 == 0xdfb4
                           00DFB4  1185 _X_ADCCON1	=	0xdfb4
                           00DFB5  1186 G$X_ADCCON2$0$0 == 0xdfb5
                           00DFB5  1187 _X_ADCCON2	=	0xdfb5
                           00DFB6  1188 G$X_ADCCON3$0$0 == 0xdfb6
                           00DFB6  1189 _X_ADCCON3	=	0xdfb6
                           00DFB7  1190 G$_X_SFRB7$0$0 == 0xdfb7
                           00DFB7  1191 __X_SFRB7	=	0xdfb7
                           00DFB8  1192 G$_NA_IEN1$0$0 == 0xdfb8
                           00DFB8  1193 __NA_IEN1	=	0xdfb8
                           00DFB9  1194 G$_NA_IP1$0$0 == 0xdfb9
                           00DFB9  1195 __NA_IP1	=	0xdfb9
                           00DFBA  1196 G$X_ADCL$0$0 == 0xdfba
                           00DFBA  1197 _X_ADCL	=	0xdfba
                           00DFBB  1198 G$X_ADCH$0$0 == 0xdfbb
                           00DFBB  1199 _X_ADCH	=	0xdfbb
                           00DFBC  1200 G$X_RNDL$0$0 == 0xdfbc
                           00DFBC  1201 _X_RNDL	=	0xdfbc
                           00DFBD  1202 G$X_RNDH$0$0 == 0xdfbd
                           00DFBD  1203 _X_RNDH	=	0xdfbd
                           00DFBE  1204 G$X_SLEEP$0$0 == 0xdfbe
                           00DFBE  1205 _X_SLEEP	=	0xdfbe
                           00DFBF  1206 G$_X_SFRBF$0$0 == 0xdfbf
                           00DFBF  1207 __X_SFRBF	=	0xdfbf
                           00DFC0  1208 G$_NA_IRCON$0$0 == 0xdfc0
                           00DFC0  1209 __NA_IRCON	=	0xdfc0
                           00DFC1  1210 G$X_U0DBUF$0$0 == 0xdfc1
                           00DFC1  1211 _X_U0DBUF	=	0xdfc1
                           00DFC2  1212 G$X_U0BAUD$0$0 == 0xdfc2
                           00DFC2  1213 _X_U0BAUD	=	0xdfc2
                           00DFC3  1214 G$_X_SFRC3$0$0 == 0xdfc3
                           00DFC3  1215 __X_SFRC3	=	0xdfc3
                           00DFC4  1216 G$X_U0UCR$0$0 == 0xdfc4
                           00DFC4  1217 _X_U0UCR	=	0xdfc4
                           00DFC5  1218 G$X_U0GCR$0$0 == 0xdfc5
                           00DFC5  1219 _X_U0GCR	=	0xdfc5
                           00DFC6  1220 G$X_CLKCON$0$0 == 0xdfc6
                           00DFC6  1221 _X_CLKCON	=	0xdfc6
                           00DFC7  1222 G$X_MEMCTR$0$0 == 0xdfc7
                           00DFC7  1223 _X_MEMCTR	=	0xdfc7
                           00DFC8  1224 G$_X_SFRC8$0$0 == 0xdfc8
                           00DFC8  1225 __X_SFRC8	=	0xdfc8
                           00DFC9  1226 G$X_WDCTL$0$0 == 0xdfc9
                           00DFC9  1227 _X_WDCTL	=	0xdfc9
                           00DFCA  1228 G$X_T3CNT$0$0 == 0xdfca
                           00DFCA  1229 _X_T3CNT	=	0xdfca
                           00DFCB  1230 G$X_T3CTL$0$0 == 0xdfcb
                           00DFCB  1231 _X_T3CTL	=	0xdfcb
                           00DFCC  1232 G$X_T3CCTL0$0$0 == 0xdfcc
                           00DFCC  1233 _X_T3CCTL0	=	0xdfcc
                           00DFCD  1234 G$X_T3CC0$0$0 == 0xdfcd
                           00DFCD  1235 _X_T3CC0	=	0xdfcd
                           00DFCE  1236 G$X_T3CCTL1$0$0 == 0xdfce
                           00DFCE  1237 _X_T3CCTL1	=	0xdfce
                           00DFCF  1238 G$X_T3CC1$0$0 == 0xdfcf
                           00DFCF  1239 _X_T3CC1	=	0xdfcf
                           00DFD0  1240 G$_NA_PSW$0$0 == 0xdfd0
                           00DFD0  1241 __NA_PSW	=	0xdfd0
                           00DFD1  1242 G$X_DMAIRQ$0$0 == 0xdfd1
                           00DFD1  1243 _X_DMAIRQ	=	0xdfd1
                           00DFD2  1244 G$X_DMA1CFGL$0$0 == 0xdfd2
                           00DFD2  1245 _X_DMA1CFGL	=	0xdfd2
                           00DFD3  1246 G$X_DMA1CFGH$0$0 == 0xdfd3
                           00DFD3  1247 _X_DMA1CFGH	=	0xdfd3
                           00DFD4  1248 G$X_DMA0CFGL$0$0 == 0xdfd4
                           00DFD4  1249 _X_DMA0CFGL	=	0xdfd4
                           00DFD5  1250 G$X_DMA0CFGH$0$0 == 0xdfd5
                           00DFD5  1251 _X_DMA0CFGH	=	0xdfd5
                           00DFD6  1252 G$X_DMAARM$0$0 == 0xdfd6
                           00DFD6  1253 _X_DMAARM	=	0xdfd6
                           00DFD7  1254 G$X_DMAREQ$0$0 == 0xdfd7
                           00DFD7  1255 _X_DMAREQ	=	0xdfd7
                           00DFD8  1256 G$X_TIMIF$0$0 == 0xdfd8
                           00DFD8  1257 _X_TIMIF	=	0xdfd8
                           00DFD9  1258 G$X_RFD$0$0 == 0xdfd9
                           00DFD9  1259 _X_RFD	=	0xdfd9
                           00DFDA  1260 G$X_T1CC0L$0$0 == 0xdfda
                           00DFDA  1261 _X_T1CC0L	=	0xdfda
                           00DFDB  1262 G$X_T1CC0H$0$0 == 0xdfdb
                           00DFDB  1263 _X_T1CC0H	=	0xdfdb
                           00DFDC  1264 G$X_T1CC1L$0$0 == 0xdfdc
                           00DFDC  1265 _X_T1CC1L	=	0xdfdc
                           00DFDD  1266 G$X_T1CC1H$0$0 == 0xdfdd
                           00DFDD  1267 _X_T1CC1H	=	0xdfdd
                           00DFDE  1268 G$X_T1CC2L$0$0 == 0xdfde
                           00DFDE  1269 _X_T1CC2L	=	0xdfde
                           00DFDF  1270 G$X_T1CC2H$0$0 == 0xdfdf
                           00DFDF  1271 _X_T1CC2H	=	0xdfdf
                           00DFE0  1272 G$_NA_ACC$0$0 == 0xdfe0
                           00DFE0  1273 __NA_ACC	=	0xdfe0
                           00DFE1  1274 G$X_RFST$0$0 == 0xdfe1
                           00DFE1  1275 _X_RFST	=	0xdfe1
                           00DFE2  1276 G$X_T1CNTL$0$0 == 0xdfe2
                           00DFE2  1277 _X_T1CNTL	=	0xdfe2
                           00DFE3  1278 G$X_T1CNTH$0$0 == 0xdfe3
                           00DFE3  1279 _X_T1CNTH	=	0xdfe3
                           00DFE4  1280 G$X_T1CTL$0$0 == 0xdfe4
                           00DFE4  1281 _X_T1CTL	=	0xdfe4
                           00DFE5  1282 G$X_T1CCTL0$0$0 == 0xdfe5
                           00DFE5  1283 _X_T1CCTL0	=	0xdfe5
                           00DFE6  1284 G$X_T1CCTL1$0$0 == 0xdfe6
                           00DFE6  1285 _X_T1CCTL1	=	0xdfe6
                           00DFE7  1286 G$X_T1CCTL2$0$0 == 0xdfe7
                           00DFE7  1287 _X_T1CCTL2	=	0xdfe7
                           00DFE8  1288 G$_NA_IRCON2$0$0 == 0xdfe8
                           00DFE8  1289 __NA_IRCON2	=	0xdfe8
                           00DFE9  1290 G$X_RFIF$0$0 == 0xdfe9
                           00DFE9  1291 _X_RFIF	=	0xdfe9
                           00DFEA  1292 G$X_T4CNT$0$0 == 0xdfea
                           00DFEA  1293 _X_T4CNT	=	0xdfea
                           00DFEB  1294 G$X_T4CTL$0$0 == 0xdfeb
                           00DFEB  1295 _X_T4CTL	=	0xdfeb
                           00DFEC  1296 G$X_T4CCTL0$0$0 == 0xdfec
                           00DFEC  1297 _X_T4CCTL0	=	0xdfec
                           00DFED  1298 G$X_T4CC0$0$0 == 0xdfed
                           00DFED  1299 _X_T4CC0	=	0xdfed
                           00DFEE  1300 G$X_T4CCTL1$0$0 == 0xdfee
                           00DFEE  1301 _X_T4CCTL1	=	0xdfee
                           00DFEF  1302 G$X_T4CC1$0$0 == 0xdfef
                           00DFEF  1303 _X_T4CC1	=	0xdfef
                           00DFF0  1304 G$_NA_B$0$0 == 0xdff0
                           00DFF0  1305 __NA_B	=	0xdff0
                           00DFF1  1306 G$X_PERCFG$0$0 == 0xdff1
                           00DFF1  1307 _X_PERCFG	=	0xdff1
                           00DFF2  1308 G$X_ADCCFG$0$0 == 0xdff2
                           00DFF2  1309 _X_ADCCFG	=	0xdff2
                           00DFF3  1310 G$X_P0SEL$0$0 == 0xdff3
                           00DFF3  1311 _X_P0SEL	=	0xdff3
                           00DFF4  1312 G$X_P1SEL$0$0 == 0xdff4
                           00DFF4  1313 _X_P1SEL	=	0xdff4
                           00DFF5  1314 G$X_P2SEL$0$0 == 0xdff5
                           00DFF5  1315 _X_P2SEL	=	0xdff5
                           00DFF6  1316 G$X_P1INP$0$0 == 0xdff6
                           00DFF6  1317 _X_P1INP	=	0xdff6
                           00DFF7  1318 G$X_P2INP$0$0 == 0xdff7
                           00DFF7  1319 _X_P2INP	=	0xdff7
                           00DFF8  1320 G$X_U1CSR$0$0 == 0xdff8
                           00DFF8  1321 _X_U1CSR	=	0xdff8
                           00DFF9  1322 G$X_U1DBUF$0$0 == 0xdff9
                           00DFF9  1323 _X_U1DBUF	=	0xdff9
                           00DFFA  1324 G$X_U1BAUD$0$0 == 0xdffa
                           00DFFA  1325 _X_U1BAUD	=	0xdffa
                           00DFFB  1326 G$X_U1UCR$0$0 == 0xdffb
                           00DFFB  1327 _X_U1UCR	=	0xdffb
                           00DFFC  1328 G$X_U1GCR$0$0 == 0xdffc
                           00DFFC  1329 _X_U1GCR	=	0xdffc
                           00DFFD  1330 G$X_P0DIR$0$0 == 0xdffd
                           00DFFD  1331 _X_P0DIR	=	0xdffd
                           00DFFE  1332 G$X_P1DIR$0$0 == 0xdffe
                           00DFFE  1333 _X_P1DIR	=	0xdffe
                           00DFFF  1334 G$X_P2DIR$0$0 == 0xdfff
                           00DFFF  1335 _X_P2DIR	=	0xdfff
                           000000  1336 Lhal_mcu.halMcuWaitUs$usec$1$12==.
      00023F                       1337 _halMcuWaitUs_usec_1_12:
      00023F                       1338 	.ds 2
                           000002  1339 Lhal_mcu.halMcuWaitMs$msec$1$15==.
      000241                       1340 _halMcuWaitMs_msec_1_15:
      000241                       1341 	.ds 2
                                   1342 ;--------------------------------------------------------
                                   1343 ; absolute external ram data
                                   1344 ;--------------------------------------------------------
                                   1345 	.area XABS    (ABS,XDATA)
                                   1346 ;--------------------------------------------------------
                                   1347 ; external initialized ram data
                                   1348 ;--------------------------------------------------------
                                   1349 	.area XISEG   (XDATA)
                                   1350 	.area HOME    (CODE)
                                   1351 	.area GSINIT0 (CODE)
                                   1352 	.area GSINIT1 (CODE)
                                   1353 	.area GSINIT2 (CODE)
                                   1354 	.area GSINIT3 (CODE)
                                   1355 	.area GSINIT4 (CODE)
                                   1356 	.area GSINIT5 (CODE)
                                   1357 	.area GSINIT  (CODE)
                                   1358 	.area GSFINAL (CODE)
                                   1359 	.area CSEG    (CODE)
                                   1360 ;--------------------------------------------------------
                                   1361 ; global & static initialisations
                                   1362 ;--------------------------------------------------------
                                   1363 	.area HOME    (CODE)
                                   1364 	.area GSINIT  (CODE)
                                   1365 	.area GSFINAL (CODE)
                                   1366 	.area GSINIT  (CODE)
                                   1367 ;--------------------------------------------------------
                                   1368 ; Home
                                   1369 ;--------------------------------------------------------
                                   1370 	.area HOME    (CODE)
                                   1371 	.area HOME    (CODE)
                                   1372 ;--------------------------------------------------------
                                   1373 ; code
                                   1374 ;--------------------------------------------------------
                                   1375 	.area CSEG    (CODE)
                                   1376 ;------------------------------------------------------------
                                   1377 ;Allocation info for local variables in function 'halMcuInit'
                                   1378 ;------------------------------------------------------------
                           000000  1379 	G$halMcuInit$0$0 ==.
                           000000  1380 	C$hal_mcu.c$23$0$0 ==.
                                   1381 ;	hal_mcu.c:23: void halMcuInit( void ) {
                                   1382 ;	-----------------------------------------
                                   1383 ;	 function halMcuInit
                                   1384 ;	-----------------------------------------
      000A94                       1385 _halMcuInit:
                           000007  1386 	ar7 = 0x07
                           000006  1387 	ar6 = 0x06
                           000005  1388 	ar5 = 0x05
                           000004  1389 	ar4 = 0x04
                           000003  1390 	ar3 = 0x03
                           000002  1391 	ar2 = 0x02
                           000001  1392 	ar1 = 0x01
                           000000  1393 	ar0 = 0x00
                           000000  1394 	C$hal_mcu.c$24$1$11 ==.
                                   1395 ;	hal_mcu.c:24: clockSetMainSrc( CLOCK_SRC_XOSC );
      000A94 75 82 00         [24] 1396 	mov	dpl,#0x00
      000A97 12 00 62         [24] 1397 	lcall	_clockSetMainSrc
                           000006  1398 	C$hal_mcu.c$25$1$11 ==.
                           000006  1399 	XG$halMcuInit$0$0 ==.
      000A9A 22               [24] 1400 	ret
                                   1401 ;------------------------------------------------------------
                                   1402 ;Allocation info for local variables in function 'halMcuWaitUs'
                                   1403 ;------------------------------------------------------------
                                   1404 ;usec                      Allocated with name '_halMcuWaitUs_usec_1_12'
                                   1405 ;------------------------------------------------------------
                           000007  1406 	G$halMcuWaitUs$0$0 ==.
                           000007  1407 	C$hal_mcu.c$46$1$11 ==.
                                   1408 ;	hal_mcu.c:46: void halMcuWaitUs( uint16_t usec ) {
                                   1409 ;	-----------------------------------------
                                   1410 ;	 function halMcuWaitUs
                                   1411 ;	-----------------------------------------
      000A9B                       1412 _halMcuWaitUs:
      000A9B AF 83            [24] 1413 	mov	r7,dph
      000A9D E5 82            [12] 1414 	mov	a,dpl
      000A9F 90 02 3F         [24] 1415 	mov	dptr,#_halMcuWaitUs_usec_1_12
      000AA2 F0               [24] 1416 	movx	@dptr,a
      000AA3 EF               [12] 1417 	mov	a,r7
      000AA4 A3               [24] 1418 	inc	dptr
      000AA5 F0               [24] 1419 	movx	@dptr,a
                           000012  1420 	C$hal_mcu.c$47$1$13 ==.
                                   1421 ;	hal_mcu.c:47: usec >>= 1;          // Divide by 2 to achieve better resolution
      000AA6 90 02 3F         [24] 1422 	mov	dptr,#_halMcuWaitUs_usec_1_12
      000AA9 E0               [24] 1423 	movx	a,@dptr
      000AAA FE               [12] 1424 	mov	r6,a
      000AAB A3               [24] 1425 	inc	dptr
      000AAC E0               [24] 1426 	movx	a,@dptr
      000AAD C3               [12] 1427 	clr	c
      000AAE 13               [12] 1428 	rrc	a
      000AAF CE               [12] 1429 	xch	a,r6
      000AB0 13               [12] 1430 	rrc	a
      000AB1 CE               [12] 1431 	xch	a,r6
      000AB2 FF               [12] 1432 	mov	r7,a
      000AB3 90 02 3F         [24] 1433 	mov	dptr,#_halMcuWaitUs_usec_1_12
      000AB6 EE               [12] 1434 	mov	a,r6
      000AB7 F0               [24] 1435 	movx	@dptr,a
      000AB8 EF               [12] 1436 	mov	a,r7
      000AB9 A3               [24] 1437 	inc	dptr
      000ABA F0               [24] 1438 	movx	@dptr,a
                           000027  1439 	C$hal_mcu.c$49$1$13 ==.
                                   1440 ;	hal_mcu.c:49: while( usec > 1 ) {   // compare: ~13 cycles
      000ABB                       1441 00101$:
      000ABB 90 02 3F         [24] 1442 	mov	dptr,#_halMcuWaitUs_usec_1_12
      000ABE E0               [24] 1443 	movx	a,@dptr
      000ABF FE               [12] 1444 	mov	r6,a
      000AC0 A3               [24] 1445 	inc	dptr
      000AC1 E0               [24] 1446 	movx	a,@dptr
      000AC2 FF               [12] 1447 	mov	r7,a
      000AC3 C3               [12] 1448 	clr	c
      000AC4 74 01            [12] 1449 	mov	a,#0x01
      000AC6 9E               [12] 1450 	subb	a,r6
      000AC7 E4               [12] 1451 	clr	a
      000AC8 9F               [12] 1452 	subb	a,r7
      000AC9 50 20            [24] 1453 	jnc	00104$
                           000037  1454 	C$hal_mcu.c$50$2$14 ==.
                                   1455 ;	hal_mcu.c:50: Nop( );     // 1 cycle/NOP
      000ACB 00               [12] 1456 	nop 
                           000038  1457 	C$hal_mcu.c$51$2$14 ==.
                                   1458 ;	hal_mcu.c:51: Nop( );
      000ACC 00               [12] 1459 	nop 
                           000039  1460 	C$hal_mcu.c$52$2$14 ==.
                                   1461 ;	hal_mcu.c:52: Nop( );
      000ACD 00               [12] 1462 	nop 
                           00003A  1463 	C$hal_mcu.c$53$2$14 ==.
                                   1464 ;	hal_mcu.c:53: Nop( );
      000ACE 00               [12] 1465 	nop 
                           00003B  1466 	C$hal_mcu.c$54$2$14 ==.
                                   1467 ;	hal_mcu.c:54: Nop( );
      000ACF 00               [12] 1468 	nop 
                           00003C  1469 	C$hal_mcu.c$55$2$14 ==.
                                   1470 ;	hal_mcu.c:55: Nop( );
      000AD0 00               [12] 1471 	nop 
                           00003D  1472 	C$hal_mcu.c$56$2$14 ==.
                                   1473 ;	hal_mcu.c:56: Nop( );
      000AD1 00               [12] 1474 	nop 
                           00003E  1475 	C$hal_mcu.c$57$2$14 ==.
                                   1476 ;	hal_mcu.c:57: Nop( );
      000AD2 00               [12] 1477 	nop 
                           00003F  1478 	C$hal_mcu.c$58$2$14 ==.
                                   1479 ;	hal_mcu.c:58: Nop( );
      000AD3 00               [12] 1480 	nop 
                           000040  1481 	C$hal_mcu.c$59$2$14 ==.
                                   1482 ;	hal_mcu.c:59: Nop( );
      000AD4 00               [12] 1483 	nop 
                           000041  1484 	C$hal_mcu.c$61$2$14 ==.
                                   1485 ;	hal_mcu.c:61: usec--;        // decr: ~7 cycles
      000AD5 90 02 3F         [24] 1486 	mov	dptr,#_halMcuWaitUs_usec_1_12
      000AD8 E0               [24] 1487 	movx	a,@dptr
      000AD9 24 FF            [12] 1488 	add	a,#0xFF
      000ADB FE               [12] 1489 	mov	r6,a
      000ADC A3               [24] 1490 	inc	dptr
      000ADD E0               [24] 1491 	movx	a,@dptr
      000ADE 34 FF            [12] 1492 	addc	a,#0xFF
      000AE0 FF               [12] 1493 	mov	r7,a
      000AE1 90 02 3F         [24] 1494 	mov	dptr,#_halMcuWaitUs_usec_1_12
      000AE4 EE               [12] 1495 	mov	a,r6
      000AE5 F0               [24] 1496 	movx	@dptr,a
      000AE6 EF               [12] 1497 	mov	a,r7
      000AE7 A3               [24] 1498 	inc	dptr
      000AE8 F0               [24] 1499 	movx	@dptr,a
      000AE9 80 D0            [24] 1500 	sjmp	00101$
      000AEB                       1501 00104$:
                           000057  1502 	C$hal_mcu.c$63$1$13 ==.
                           000057  1503 	XG$halMcuWaitUs$0$0 ==.
      000AEB 22               [24] 1504 	ret
                                   1505 ;------------------------------------------------------------
                                   1506 ;Allocation info for local variables in function 'halMcuWaitMs'
                                   1507 ;------------------------------------------------------------
                                   1508 ;msec                      Allocated with name '_halMcuWaitMs_msec_1_15'
                                   1509 ;------------------------------------------------------------
                           000058  1510 	G$halMcuWaitMs$0$0 ==.
                           000058  1511 	C$hal_mcu.c$84$1$13 ==.
                                   1512 ;	hal_mcu.c:84: void halMcuWaitMs( uint16_t msec ) {
                                   1513 ;	-----------------------------------------
                                   1514 ;	 function halMcuWaitMs
                                   1515 ;	-----------------------------------------
      000AEC                       1516 _halMcuWaitMs:
      000AEC AF 83            [24] 1517 	mov	r7,dph
      000AEE E5 82            [12] 1518 	mov	a,dpl
      000AF0 90 02 41         [24] 1519 	mov	dptr,#_halMcuWaitMs_msec_1_15
      000AF3 F0               [24] 1520 	movx	@dptr,a
      000AF4 EF               [12] 1521 	mov	a,r7
      000AF5 A3               [24] 1522 	inc	dptr
      000AF6 F0               [24] 1523 	movx	@dptr,a
                           000063  1524 	C$hal_mcu.c$85$1$16 ==.
                                   1525 ;	hal_mcu.c:85: while( msec-- ) {
      000AF7                       1526 00101$:
      000AF7 90 02 41         [24] 1527 	mov	dptr,#_halMcuWaitMs_msec_1_15
      000AFA E0               [24] 1528 	movx	a,@dptr
      000AFB FE               [12] 1529 	mov	r6,a
      000AFC A3               [24] 1530 	inc	dptr
      000AFD E0               [24] 1531 	movx	a,@dptr
      000AFE FF               [12] 1532 	mov	r7,a
      000AFF EE               [12] 1533 	mov	a,r6
      000B00 24 FF            [12] 1534 	add	a,#0xFF
      000B02 FC               [12] 1535 	mov	r4,a
      000B03 EF               [12] 1536 	mov	a,r7
      000B04 34 FF            [12] 1537 	addc	a,#0xFF
      000B06 FD               [12] 1538 	mov	r5,a
      000B07 90 02 41         [24] 1539 	mov	dptr,#_halMcuWaitMs_msec_1_15
      000B0A EC               [12] 1540 	mov	a,r4
      000B0B F0               [24] 1541 	movx	@dptr,a
      000B0C ED               [12] 1542 	mov	a,r5
      000B0D A3               [24] 1543 	inc	dptr
      000B0E F0               [24] 1544 	movx	@dptr,a
      000B0F EE               [12] 1545 	mov	a,r6
      000B10 4F               [12] 1546 	orl	a,r7
      000B11 60 08            [24] 1547 	jz	00104$
                           00007F  1548 	C$hal_mcu.c$86$2$17 ==.
                                   1549 ;	hal_mcu.c:86: halMcuWaitUs( 1000 );
      000B13 90 03 E8         [24] 1550 	mov	dptr,#0x03E8
      000B16 12 0A 9B         [24] 1551 	lcall	_halMcuWaitUs
      000B19 80 DC            [24] 1552 	sjmp	00101$
      000B1B                       1553 00104$:
                           000087  1554 	C$hal_mcu.c$88$1$16 ==.
                           000087  1555 	XG$halMcuWaitMs$0$0 ==.
      000B1B 22               [24] 1556 	ret
                                   1557 ;------------------------------------------------------------
                                   1558 ;Allocation info for local variables in function 'halMcuSetLowPowerMode'
                                   1559 ;------------------------------------------------------------
                                   1560 ;mode                      Allocated with name '_halMcuSetLowPowerMode_mode_1_18'
                                   1561 ;------------------------------------------------------------
                           000088  1562 	G$halMcuSetLowPowerMode$0$0 ==.
                           000088  1563 	C$hal_mcu.c$104$1$16 ==.
                                   1564 ;	hal_mcu.c:104: void halMcuSetLowPowerMode( uint8_t mode ) {
                                   1565 ;	-----------------------------------------
                                   1566 ;	 function halMcuSetLowPowerMode
                                   1567 ;	-----------------------------------------
      000B1C                       1568 _halMcuSetLowPowerMode:
                           000088  1569 	C$hal_mcu.c$105$1$19 ==.
                                   1570 ;	hal_mcu.c:105: mode;
                           000088  1571 	C$hal_mcu.c$108$1$19 ==.
                           000088  1572 	XG$halMcuSetLowPowerMode$0$0 ==.
      000B1C 22               [24] 1573 	ret
                                   1574 ;------------------------------------------------------------
                                   1575 ;Allocation info for local variables in function 'halMcuReset'
                                   1576 ;------------------------------------------------------------
                                   1577 ;WDT_INTERVAL_MSEC_2       Allocated with name '_halMcuReset_WDT_INTERVAL_MSEC_2_1_21'
                                   1578 ;------------------------------------------------------------
                           000089  1579 	G$halMcuReset$0$0 ==.
                           000089  1580 	C$hal_mcu.c$124$1$19 ==.
                                   1581 ;	hal_mcu.c:124: void halMcuReset( void ) {
                                   1582 ;	-----------------------------------------
                                   1583 ;	 function halMcuReset
                                   1584 ;	-----------------------------------------
      000B1D                       1585 _halMcuReset:
                           000089  1586 	C$hal_mcu.c$127$1$21 ==.
                                   1587 ;	hal_mcu.c:127: WDCTL = ((WDCTL & 0xFC) | (WDT_INTERVAL_MSEC_2 & 0x03));
      000B1D 74 FC            [12] 1588 	mov	a,#0xFC
      000B1F 55 C9            [12] 1589 	anl	a,_WDCTL
      000B21 44 03            [12] 1590 	orl	a,#0x03
      000B23 F5 C9            [12] 1591 	mov	_WDCTL,a
                           000091  1592 	C$hal_mcu.c$129$1$21 ==.
                                   1593 ;	hal_mcu.c:129: WDCTL &= ~0x04;     // Select watchdog mode
      000B25 AF C9            [24] 1594 	mov	r7,_WDCTL
      000B27 74 FB            [12] 1595 	mov	a,#0xFB
      000B29 5F               [12] 1596 	anl	a,r7
      000B2A F5 C9            [12] 1597 	mov	_WDCTL,a
                           000098  1598 	C$hal_mcu.c$130$1$21 ==.
                                   1599 ;	hal_mcu.c:130: WDCTL |= 0x08;      // Enable timer
      000B2C 43 C9 08         [24] 1600 	orl	_WDCTL,#0x08
                           00009B  1601 	C$hal_mcu.c$131$1$21 ==.
                                   1602 ;	hal_mcu.c:131: while( 1 );           // Halt here until reset
      000B2F                       1603 00102$:
      000B2F 80 FE            [24] 1604 	sjmp	00102$
                           00009D  1605 	C$hal_mcu.c$132$1$21 ==.
                           00009D  1606 	XG$halMcuReset$0$0 ==.
      000B31 22               [24] 1607 	ret
                                   1608 	.area CSEG    (CODE)
                                   1609 	.area CONST   (CODE)
                                   1610 	.area XINIT   (CODE)
                                   1611 	.area CABS    (ABS,CODE)
