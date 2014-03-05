# Register Region: SD


##Info
| Name | value |
| --- | --- |
| base | 0x7ee00000 |
| id | 0x5344434f |

##Registers

| register name | address | type | width | mask | reset |
| --- | --- | --- | --- | --- | --- |
| [SD_CS](#sd_cs) | 0x7ee00000 | RW | 25 | 0x01ffffff |  |
| [SD_SA](#sd_sa) | 0x7ee00004 | RW | 32 | 0xffffffff |  |
| [SD_SB](#sd_sb) | 0x7ee00008 | RW | 32 | 0xfff001ff |  |
| [SD_SC](#sd_sc) | 0x7ee0000c | RW | 31 | 0x7ff00f77 |  |
| [SD_PT2](#sd_pt2) | 0x7ee00010 | RW | 32 | 0xffffffff |  |
| [SD_PT1](#sd_pt1) | 0x7ee00014 | RW | 28 | 0x0fffffff |  |
| SD_IDL | 0x7ee00018 | RW | 28 | 0x0fffffff | 0000000000 |
| SD_RTC | 0x7ee0001c | RW | 32 | 0xffffffff | 0000000000 |
| SD_WTC | 0x7ee00020 | RO | 28 | 0x0fffffff | 0000000000 |
| SD_RDC | 0x7ee00024 | RO | 28 | 0x0fffffff | 0000000000 |
| SD_WDC | 0x7ee00028 | RO | 28 | 0x0fffffff | 0000000000 |
| SD_RAC | 0x7ee0002c | RO | 28 | 0x0fffffff | 0000000000 |
| SD_CYC | 0x7ee00030 | RO | 28 | 0x0fffffff | 0000000000 |
| SD_CMD | 0x7ee00034 | RO | 28 | 0x0fffffff | 0000000000 |
| SD_DAT | 0x7ee00038 | RO | 28 | 0x0fffffff | 0000000000 |
| [SD_SECSRT0](#sd_secsrt0) | 0x7ee0003c | RW | 32 | 0xffffffff |  |
| [SD_SECEND0](#sd_secend0) | 0x7ee00040 | RW | 32 | 0xffffffff |  |
| [SD_SECSRT1](#sd_secsrt1) | 0x7ee00044 | RW | 32 | 0xffffffff |  |
| [SD_SECEND1](#sd_secend1) | 0x7ee00048 | RW | 32 | 0xffffffff |  |
| [SD_SECSRT2](#sd_secsrt2) | 0x7ee0004c | RW | 32 | 0xffffffff |  |
| [SD_SECEND2](#sd_secend2) | 0x7ee00050 | RW | 32 | 0xffffffff |  |
| [SD_SECSRT3](#sd_secsrt3) | 0x7ee00054 | RW | 32 | 0xffffffff |  |
| [SD_SECEND3](#sd_secend3) | 0x7ee00058 | RW | 32 | 0xffffffff |  |
| [SD_PHYC](#sd_phyc) | 0x7ee00060 | RW | 25 | 0x01111111 |  |
| [SD_MRT](#sd_mrt) | 0x7ee00064 | RW | 9 | 0x000001ff |  |
| [SD_TMC](#sd_tmc) | 0x7ee0007c | RW | 32 | 0xffffff73 |  |
| [SD_RWC](#sd_rwc) | 0x7ee00080 | RW | 32 | 0x9fdf9f9f |  |
| SD_VAD | 0x7ee00084 | RO | 32 | 0xffffffff | 0000000000 |
| [SD_VIN](#sd_vin) | 0x7ee00088 | RW | 32 | 0x9113ffff |  |
| [SD_MR](#sd_mr) | 0x7ee00090 | RW | 32 | 0xf0ffffff |  |
| [SD_SD](#sd_sd) | 0x7ee00094 | RW | 32 | 0xf1f71fff |  |
| [SD_SE](#sd_se) | 0x7ee00098 | RW | 29 | 0x13f3f73f |  |
| SD_VER | 0x7ee0009c | RO | 32 | 0xffffffff | 0x00000009 |
| [SD_STALL](#sd_stall) | 0x7ee000a0 | RW | 10 | 0x000003ff |  |
| SD_REORD | 0x7ee000a8 | RO | 28 | 0x0fffffff | 0000000000 |
| SD_LAC | 0x7ee000ac | RO | 28 | 0x0fffffff | 0000000000 |
| SD_PRE | 0x7ee000b0 | RO | 28 | 0x0fffffff | 0000000000 |
| [SD_SF](#sd_sf) | 0x7ee000b4 | RW | 30 | 0x3fffffff |  |
| [SD_CARCRC](#sd_carcrc) | 0x7ee00100 | RO | 32 | 0xffffffff |  |
| [SD_DMRCRC0](#sd_dmrcrc0) | 0x7ee00104 | RO | 32 | 0xffffffff |  |
| [SD_DMRCRC1](#sd_dmrcrc1) | 0x7ee00108 | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC0](#sd_dqrcrc0) | 0x7ee0010c | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC1](#sd_dqrcrc1) | 0x7ee00110 | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC2](#sd_dqrcrc2) | 0x7ee00114 | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC3](#sd_dqrcrc3) | 0x7ee00118 | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC4](#sd_dqrcrc4) | 0x7ee0011c | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC5](#sd_dqrcrc5) | 0x7ee00120 | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC6](#sd_dqrcrc6) | 0x7ee00124 | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC7](#sd_dqrcrc7) | 0x7ee00128 | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC8](#sd_dqrcrc8) | 0x7ee0012c | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC9](#sd_dqrcrc9) | 0x7ee00130 | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC10](#sd_dqrcrc10) | 0x7ee00134 | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC11](#sd_dqrcrc11) | 0x7ee00138 | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC12](#sd_dqrcrc12) | 0x7ee0013c | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC13](#sd_dqrcrc13) | 0x7ee00140 | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC14](#sd_dqrcrc14) | 0x7ee00144 | RO | 32 | 0xffffffff |  |
| [SD_DQRCRC15](#sd_dqrcrc15) | 0x7ee00148 | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC0](#sd_dqlcrc0) | 0x7ee0014c | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC1](#sd_dqlcrc1) | 0x7ee00150 | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC2](#sd_dqlcrc2) | 0x7ee00154 | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC3](#sd_dqlcrc3) | 0x7ee00158 | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC4](#sd_dqlcrc4) | 0x7ee0015c | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC5](#sd_dqlcrc5) | 0x7ee00160 | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC6](#sd_dqlcrc6) | 0x7ee00164 | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC7](#sd_dqlcrc7) | 0x7ee00168 | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC8](#sd_dqlcrc8) | 0x7ee0016c | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC9](#sd_dqlcrc9) | 0x7ee00170 | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC10](#sd_dqlcrc10) | 0x7ee00174 | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC11](#sd_dqlcrc11) | 0x7ee00178 | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC12](#sd_dqlcrc12) | 0x7ee0017c | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC13](#sd_dqlcrc13) | 0x7ee00180 | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC14](#sd_dqlcrc14) | 0x7ee00184 | RO | 32 | 0xffffffff |  |
| [SD_DQLCRC15](#sd_dqlcrc15) | 0x7ee00188 | RO | 32 | 0xffffffff |  |

##Unsupported defines

| define | value |
| --- | --- |
| SD_CARCRC_FALL_RESET | 0x0 |
| SD_CARCRC_RISE_RESET | 0x0 |
| SD_CS_ASHDNE_RESET | 0x0 |
| SD_CS_ASHDN_T_RESET | 0xf |
| SD_CS_CLKOFF_RESET | 0x1 |
| SD_CS_DEL_KEEP_RESET | 0x0 |
| SD_CS_DLLCAL_RESET | 0x0 |
| SD_CS_DPD_RESET | 0x0 |
| SD_CS_EN_RESET | 0x0 |
| SD_CS_EXCEPTION_RESET | 0x0 |
| SD_CS_IDLE_RESET | 0x0 |
| SD_CS_PUSKIP_RESET | 0x0 |
| SD_CS_RDH_IDLE_RESET | 0x0 |
| SD_CS_RESTRT_RESET | 0x0 |
| SD_CS_SDTST_RESET | 0x0 |
| SD_CS_SDUP_RESET | 0x0 |
| SD_CS_SREF2RUN_RESET | 0x0 |
| SD_CS_STALLING_RESET | 0x0 |
| SD_CS_STATEN_RESET | 0x0 |
| SD_CS_STBY_RESET | 0x0 |
| SD_CS_STOP_RESET | 0x0 |
| SD_DMRCRC0_HIGH_RESET | 0x0 |
| SD_DMRCRC0_LOW_RESET | 0x0 |
| SD_DMRCRC1_HIGH_RESET | 0x0 |
| SD_DMRCRC1_LOW_RESET | 0x0 |
| SD_DQLCRC0_FALL_RESET | 0x0 |
| SD_DQLCRC0_RISE_RESET | 0x0 |
| SD_DQLCRC10_FALL_RESET | 0x0 |
| SD_DQLCRC10_RISE_RESET | 0x0 |
| SD_DQLCRC11_FALL_RESET | 0x0 |
| SD_DQLCRC11_RISE_RESET | 0x0 |
| SD_DQLCRC12_FALL_RESET | 0x0 |
| SD_DQLCRC12_RISE_RESET | 0x0 |
| SD_DQLCRC13_FALL_RESET | 0x0 |
| SD_DQLCRC13_RISE_RESET | 0x0 |
| SD_DQLCRC14_FALL_RESET | 0x0 |
| SD_DQLCRC14_RISE_RESET | 0x0 |
| SD_DQLCRC15_FALL_RESET | 0x0 |
| SD_DQLCRC15_RISE_RESET | 0x0 |
| SD_DQLCRC1_FALL_RESET | 0x0 |
| SD_DQLCRC1_RISE_RESET | 0x0 |
| SD_DQLCRC2_FALL_RESET | 0x0 |
| SD_DQLCRC2_RISE_RESET | 0x0 |
| SD_DQLCRC3_FALL_RESET | 0x0 |
| SD_DQLCRC3_RISE_RESET | 0x0 |
| SD_DQLCRC4_FALL_RESET | 0x0 |
| SD_DQLCRC4_RISE_RESET | 0x0 |
| SD_DQLCRC5_FALL_RESET | 0x0 |
| SD_DQLCRC5_RISE_RESET | 0x0 |
| SD_DQLCRC6_FALL_RESET | 0x0 |
| SD_DQLCRC6_RISE_RESET | 0x0 |
| SD_DQLCRC7_FALL_RESET | 0x0 |
| SD_DQLCRC7_RISE_RESET | 0x0 |
| SD_DQLCRC8_FALL_RESET | 0x0 |
| SD_DQLCRC8_RISE_RESET | 0x0 |
| SD_DQLCRC9_FALL_RESET | 0x0 |
| SD_DQLCRC9_RISE_RESET | 0x0 |
| SD_DQRCRC0_FALL_RESET | 0x0 |
| SD_DQRCRC0_RISE_RESET | 0x0 |
| SD_DQRCRC10_FALL_RESET | 0x0 |
| SD_DQRCRC10_RISE_RESET | 0x0 |
| SD_DQRCRC11_FALL_RESET | 0x0 |
| SD_DQRCRC11_RISE_RESET | 0x0 |
| SD_DQRCRC12_FALL_RESET | 0x0 |
| SD_DQRCRC12_RISE_RESET | 0x0 |
| SD_DQRCRC13_FALL_RESET | 0x0 |
| SD_DQRCRC13_RISE_RESET | 0x0 |
| SD_DQRCRC14_FALL_RESET | 0x0 |
| SD_DQRCRC14_RISE_RESET | 0x0 |
| SD_DQRCRC15_FALL_RESET | 0x0 |
| SD_DQRCRC15_RISE_RESET | 0x0 |
| SD_DQRCRC1_FALL_RESET | 0x0 |
| SD_DQRCRC1_RISE_RESET | 0x0 |
| SD_DQRCRC2_FALL_RESET | 0x0 |
| SD_DQRCRC2_RISE_RESET | 0x0 |
| SD_DQRCRC3_FALL_RESET | 0x0 |
| SD_DQRCRC3_RISE_RESET | 0x0 |
| SD_DQRCRC4_FALL_RESET | 0x0 |
| SD_DQRCRC4_RISE_RESET | 0x0 |
| SD_DQRCRC5_FALL_RESET | 0x0 |
| SD_DQRCRC5_RISE_RESET | 0x0 |
| SD_DQRCRC6_FALL_RESET | 0x0 |
| SD_DQRCRC6_RISE_RESET | 0x0 |
| SD_DQRCRC7_FALL_RESET | 0x0 |
| SD_DQRCRC7_RISE_RESET | 0x0 |
| SD_DQRCRC8_FALL_RESET | 0x0 |
| SD_DQRCRC8_RISE_RESET | 0x0 |
| SD_DQRCRC9_FALL_RESET | 0x0 |
| SD_DQRCRC9_RISE_RESET | 0x0 |
| SD_MRT_T_MRW_RESET | 0x4 |
| SD_MR_ADDR_RESET | 0x0 |
| SD_MR_DONE_RESET | 0x1 |
| SD_MR_HI_Z_RESET | 0x0 |
| SD_MR_RDATA_RESET | 0x0 |
| SD_MR_RW_RESET | 0x0 |
| SD_MR_TIMEOUT_RESET | 0x0 |
| SD_MR_WDATA_RESET | 0x0 |
| SD_PHYC_BIST_MODE_RESET | 0x0 |
| SD_PHYC_CRC_CLR_RESET | 0x0 |
| SD_PHYC_CRC_EN_RESET | 0x0 |
| SD_PHYC_IOB_TMODE_RESET | 0x0 |
| SD_PHYC_MDLL_TMODE_RESET | 0x0 |
| SD_PHYC_PHYRST_RESET | 0x0 |
| SD_PHYC_VREF_ENB_RESET | 0x0 |
| SD_PT1_T_INIT1_RESET | 0x28 |
| SD_PT1_T_INIT3_RESET | 0x13880 |
| SD_PT2_T_INIT5_RESET | 0xfa0 |
| SD_RWC_LASTCNT_RESET | 0x0 |
| SD_RWC_MARGIN_RESET | 0x1 |
| SD_RWC_MAXCNT_RESET | 0x0 |
| SD_RWC_RSTMAX_RESET | 0x0 |
| SD_RWC_RXOVR_RESET | 0x0 |
| SD_RWC_RXVAL_RESET | 0x0 |
| SD_RWC_WRTOVR_RESET | 0x0 |
| SD_RWC_WRTVAL_RESET | 0x0 |
| SD_SA_CLKSTOP_RESET | 0x1 |
| SD_SA_PGEHLDE_RESET | 0x0 |
| SD_SA_PGEHLD_IDL_RESET | 0x0 |
| SD_SA_POWSAVE_RESET | 0x0 |
| SD_SA_RFSH_T_RESET | 0x30c |
| SD_SB_BANKLOW_RESET | 0x0 |
| SD_SB_COLBITS_RESET | 0x1 |
| SD_SB_EIGHTBANK_RESET | 0x0 |
| SD_SB_INHIBIT_LA_RESET | 0x0 |
| SD_SB_REORDER_RESET | 0x0 |
| SD_SB_ROWBITS_RESET | 0x1 |
| SD_SB_STBY_T_RESET | 0x0 |
| SD_SC_T_RFC_RESET | 0x1e |
| SD_SC_T_RRD_RESET | 0x4 |
| SD_SC_T_WR_RESET | 0x6 |
| SD_SC_T_WTR_RESET | 0x3 |
| SD_SC_WL_RESET | 0x2 |
| SD_SD_T_RAS_RESET | 0xe |
| SD_SD_T_RCD_RESET | 0x8 |
| SD_SD_T_RC_RESET | 0x14 |
| SD_SD_T_RPab_RESET | 0xa |
| SD_SD_T_RPpb_RESET | 0x8 |
| SD_SD_T_XP_RESET | 0x2 |
| SD_SECEND0_ADDR_LS_RESET | 0xfff |
| SD_SECEND0_ADDR_MS_RESET | 0x0 |
| SD_SECEND1_ADDR_LS_RESET | 0xfff |
| SD_SECEND1_ADDR_MS_RESET | 0x0 |
| SD_SECEND2_ADDR_LS_RESET | 0xfff |
| SD_SECEND2_ADDR_MS_RESET | 0x0 |
| SD_SECEND3_ADDR_LS_RESET | 0xfff |
| SD_SECEND3_ADDR_MS_RESET | 0x0 |
| SD_SECSRT0_ADDR_LS_RESET | 0x0 |
| SD_SECSRT0_ADDR_MS_RESET | 0x0 |
| SD_SECSRT0_EN_RESET | 0x0 |
| SD_SECSRT1_ADDR_LS_RESET | 0x0 |
| SD_SECSRT1_ADDR_MS_RESET | 0x0 |
| SD_SECSRT1_EN_RESET | 0x0 |
| SD_SECSRT2_ADDR_LS_RESET | 0x0 |
| SD_SECSRT2_ADDR_MS_RESET | 0x0 |
| SD_SECSRT2_EN_RESET | 0x0 |
| SD_SECSRT3_ADDR_LS_RESET | 0x0 |
| SD_SECSRT3_ADDR_MS_RESET | 0x0 |
| SD_SECSRT3_EN_RESET | 0x0 |
| SD_SE_RL_EN_RESET | 0x0 |
| SD_SE_RL_RESET | 0x8 |
| SD_SE_T_FAW_RESET | 0x19 |
| SD_SE_T_RTP_RESET | 0x3 |
| SD_SE_T_XSR_RESET | 0x28 |
| SD_SF_MDLL_CAL_RESET | 0x12c |
| SD_SF_PGEHLD_T_RESET | 0x100 |
| SD_SF_PHYHOLD_RESET | 0x0 |
| SD_SF_POWSAV_T_RESET | 0x040 |
| SD_STALL_CYCLES_RESET | 0x0 |
| SD_TMC_IPRD_RESET | 0x0 |
| SD_TMC_IPSEL_RESET | 0x0 |
| SD_TMC_TSTCLK_RESET | 0x0 |
| SD_TMC_TSTPAT_RESET | 0x0 |
| SD_TMC_TS_RESET | 0x0 |
| SD_VIN_CLEAR_RESET | 0x0 |
| SD_VIN_ID_RESET | 0x0 |
| SD_VIN_INT_EN_RESET | 0x0 |
| SD_VIN_MULT_RESET | 0x0 |
| SD_VIN_SPLIT_RESET | 0x0 |
| SD_VIN_VIO_RESET | 0x0 |
| SD_VIN_WRITE_RESET | 0x0 |

##Register info


###SD_CS
 Address: 0x7ee00000

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_CS_RESTRT | 0 | 0 | 0x00000001 | 0xfffffffe |  |
| SD_CS_EN | 1 | 1 | 0x00000002 | 0xfffffffd |  |
| SD_CS_DPD | 2 | 2 | 0x00000004 | 0xfffffffb |  |
| SD_CS_STBY | 3 | 3 | 0x00000008 | 0xfffffff7 |  |
| SD_CS_PUSKIP | 4 | 4 | 0x00000010 | 0xffffffef |  |
| SD_CS_SDTST | 5 | 5 | 0x00000020 | 0xffffffdf |  |
| SD_CS_STATEN | 6 | 6 | 0x00000040 | 0xffffffbf |  |
| SD_CS_STOP | 7 | 7 | 0x00000080 | 0xffffff7f |  |
| SD_CS_SREF2RUN | 8 | 8 | 0x00000100 | 0xfffffeff |  |
| SD_CS_IDLE | 9 | 9 | 0x00000200 | 0xfffffdff |  |
| SD_CS_DLLCAL | 10 | 11 | 0x00000c00 | 0xfffff3ff |  |
| SD_CS_CLKOFF | 14 | 14 | 0x00004000 | 0xffffbfff |  |
| SD_CS_SDUP | 15 | 15 | 0x00008000 | 0xffff7fff |  |
| SD_CS_RDH_IDLE | 16 | 16 | 0x00010000 | 0xfffeffff |  |
| SD_CS_ASHDNE | 17 | 17 | 0x00020000 | 0xfffdffff |  |
| SD_CS_DEL_KEEP | 18 | 18 | 0x00040000 | 0xfffbffff |  |
| SD_CS_ASHDN_T | 19 | 22 | 0x00780000 | 0xff87ffff |  |
| SD_CS_EXCEPTION | 23 | 23 | 0x00800000 | 0xff7fffff |  |
| SD_CS_STALLING | 24 | 24 | 0x01000000 | 0xfeffffff |  |

###SD_SA
 Address: 0x7ee00004

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_SA_POWSAVE | 0 | 0 | 0x00000001 | 0xfffffffe |  |
| SD_SA_CLKSTOP | 7 | 7 | 0x00000080 | 0xffffff7f |  |
| SD_SA_PGEHLDE | 8 | 8 | 0x00000100 | 0xfffffeff |  |
| SD_SA_PGEHLD_IDL | 15 | 15 | 0x00008000 | 0xffff7fff |  |
| SD_SA_RFSH_T | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_SB
 Address: 0x7ee00008

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_SB_COLBITS | 0 | 1 | 0x00000003 | 0xfffffffc |  |
| SD_SB_ROWBITS | 2 | 3 | 0x0000000c | 0xfffffff3 |  |
| SD_SB_EIGHTBANK | 4 | 4 | 0x00000010 | 0xffffffef |  |
| SD_SB_BANKLOW | 5 | 6 | 0x00000060 | 0xffffff9f |  |
| SD_SB_REORDER | 7 | 7 | 0x00000080 | 0xffffff7f |  |
| SD_SB_INHIBIT_LA | 8 | 8 | 0x00000100 | 0xfffffeff |  |
| SD_SB_STBY_T | 20 | 31 | 0xfff00000 | 0x000fffff |  |

###SD_SC
 Address: 0x7ee0000c

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_SC_WL | 0 | 2 | 0x00000007 | 0xfffffff8 |  |
| SD_SC_T_WTR | 4 | 6 | 0x00000070 | 0xffffff8f |  |
| SD_SC_T_WR | 8 | 11 | 0x00000f00 | 0xfffff0ff |  |
| SD_SC_T_RRD | 20 | 23 | 0x00f00000 | 0xff0fffff |  |
| SD_SC_T_RFC | 24 | 30 | 0x7f000000 | 0x80ffffff |  |

###SD_PT2
 Address: 0x7ee00010

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_PT2_T_INIT5 | 0 | 15 | 0x0000ffff | 0xffff0000 |  |

###SD_PT1
 Address: 0x7ee00014

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_PT1_T_INIT1 | 0 | 7 | 0x000000ff | 0xffffff00 |  |
| SD_PT1_T_INIT3 | 8 | 27 | 0x0fffff00 | 0xf00000ff |  |

###SD_SECSRT0
 Address: 0x7ee0003c

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_SECSRT0_EN | 0 | 0 | 0x00000001 | 0xfffffffe |  |
| SD_SECSRT0_ADDR_LS | 1 | 12 | 0x00001ffe | 0xffffe001 |  |
| SD_SECSRT0_ADDR_MS | 13 | 31 | 0xffffe000 | 0x00001fff |  |

###SD_SECEND0
 Address: 0x7ee00040

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_SECEND0_ADDR_LS | 0 | 12 | 0x00001fff | 0xffffe000 |  |
| SD_SECEND0_ADDR_MS | 13 | 31 | 0xffffe000 | 0x00001fff |  |

###SD_SECSRT1
 Address: 0x7ee00044

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_SECSRT1_EN | 0 | 0 | 0x00000001 | 0xfffffffe |  |
| SD_SECSRT1_ADDR_LS | 1 | 12 | 0x00001ffe | 0xffffe001 |  |
| SD_SECSRT1_ADDR_MS | 13 | 31 | 0xffffe000 | 0x00001fff |  |

###SD_SECEND1
 Address: 0x7ee00048

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_SECEND1_ADDR_LS | 0 | 12 | 0x00001fff | 0xffffe000 |  |
| SD_SECEND1_ADDR_MS | 13 | 31 | 0xffffe000 | 0x00001fff |  |

###SD_SECSRT2
 Address: 0x7ee0004c

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_SECSRT2_EN | 0 | 0 | 0x00000001 | 0xfffffffe |  |
| SD_SECSRT2_ADDR_LS | 1 | 12 | 0x00001ffe | 0xffffe001 |  |
| SD_SECSRT2_ADDR_MS | 13 | 31 | 0xffffe000 | 0x00001fff |  |

###SD_SECEND2
 Address: 0x7ee00050

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_SECEND2_ADDR_LS | 0 | 12 | 0x00001fff | 0xffffe000 |  |
| SD_SECEND2_ADDR_MS | 13 | 31 | 0xffffe000 | 0x00001fff |  |

###SD_SECSRT3
 Address: 0x7ee00054

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_SECSRT3_EN | 0 | 0 | 0x00000001 | 0xfffffffe |  |
| SD_SECSRT3_ADDR_LS | 1 | 12 | 0x00001ffe | 0xffffe001 |  |
| SD_SECSRT3_ADDR_MS | 13 | 31 | 0xffffe000 | 0x00001fff |  |

###SD_SECEND3
 Address: 0x7ee00058

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_SECEND3_ADDR_LS | 0 | 12 | 0x00001fff | 0xffffe000 |  |
| SD_SECEND3_ADDR_MS | 13 | 31 | 0xffffe000 | 0x00001fff |  |

###SD_PHYC
 Address: 0x7ee00060

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_PHYC_PHYRST | 0 | 0 | 0x00000001 | 0xfffffffe |  |
| SD_PHYC_VREF_ENB | 4 | 4 | 0x00000010 | 0xffffffef |  |
| SD_PHYC_BIST_MODE | 8 | 8 | 0x00000100 | 0xfffffeff |  |
| SD_PHYC_IOB_TMODE | 12 | 12 | 0x00001000 | 0xffffefff |  |
| SD_PHYC_MDLL_TMODE | 16 | 16 | 0x00010000 | 0xfffeffff |  |
| SD_PHYC_CRC_EN | 20 | 20 | 0x00100000 | 0xffefffff |  |
| SD_PHYC_CRC_CLR | 24 | 24 | 0x01000000 | 0xfeffffff |  |

###SD_MRT
 Address: 0x7ee00064

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_MRT_T_MRW | 0 | 8 | 0x000001ff | 0xfffffe00 |  |

###SD_TMC
 Address: 0x7ee0007c

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_TMC_TSTCLK | 0 | 0 | 0x00000001 | 0xfffffffe |  |
| SD_TMC_TS | 1 | 1 | 0x00000002 | 0xfffffffd |  |
| SD_TMC_IPSEL | 4 | 6 | 0x00000070 | 0xffffff8f |  |
| SD_TMC_IPRD | 8 | 15 | 0x0000ff00 | 0xffff00ff |  |
| SD_TMC_TSTPAT | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_RWC
 Address: 0x7ee00080

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_RWC_RXVAL | 0 | 4 | 0x0000001f | 0xffffffe0 |  |
| SD_RWC_RXOVR | 7 | 7 | 0x00000080 | 0xffffff7f |  |
| SD_RWC_WRTVAL | 8 | 12 | 0x00001f00 | 0xffffe0ff |  |
| SD_RWC_WRTOVR | 15 | 15 | 0x00008000 | 0xffff7fff |  |
| SD_RWC_LASTCNT | 16 | 20 | 0x001f0000 | 0xffe0ffff |  |
| SD_RWC_MARGIN | 22 | 23 | 0x00c00000 | 0xff3fffff |  |
| SD_RWC_MAXCNT | 24 | 28 | 0x1f000000 | 0xe0ffffff |  |
| SD_RWC_RSTMAX | 31 | 31 | 0x80000000 | 0x7fffffff |  |

###SD_VIN
 Address: 0x7ee00088

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_VIN_ID | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_VIN_WRITE | 16 | 16 | 0x00010000 | 0xfffeffff |  |
| SD_VIN_SPLIT | 17 | 17 | 0x00020000 | 0xfffdffff |  |
| SD_VIN_VIO | 20 | 20 | 0x00100000 | 0xffefffff |  |
| SD_VIN_MULT | 24 | 24 | 0x01000000 | 0xfeffffff |  |
| SD_VIN_INT_EN | 28 | 28 | 0x10000000 | 0xefffffff |  |
| SD_VIN_CLEAR | 31 | 31 | 0x80000000 | 0x7fffffff |  |

###SD_MR
 Address: 0x7ee00090

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_MR_ADDR | 0 | 7 | 0x000000ff | 0xffffff00 |  |
| SD_MR_WDATA | 8 | 15 | 0x0000ff00 | 0xffff00ff |  |
| SD_MR_RDATA | 16 | 23 | 0x00ff0000 | 0xff00ffff |  |
| SD_MR_RW | 28 | 28 | 0x10000000 | 0xefffffff |  |
| SD_MR_HI_Z | 29 | 29 | 0x20000000 | 0xdfffffff |  |
| SD_MR_TIMEOUT | 30 | 30 | 0x40000000 | 0xbfffffff |  |
| SD_MR_DONE | 31 | 31 | 0x80000000 | 0x7fffffff |  |

###SD_SD
 Address: 0x7ee00094

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_SD_T_RCD | 0 | 3 | 0x0000000f | 0xfffffff0 |  |
| SD_SD_T_RPpb | 4 | 7 | 0x000000f0 | 0xffffff0f |  |
| SD_SD_T_RAS | 8 | 12 | 0x00001f00 | 0xffffe0ff |  |
| SD_SD_T_XP | 16 | 18 | 0x00070000 | 0xfff8ffff |  |
| SD_SD_T_RC | 20 | 24 | 0x01f00000 | 0xfe0fffff |  |
| SD_SD_T_RPab | 28 | 31 | 0xf0000000 | 0x0fffffff |  |

###SD_SE
 Address: 0x7ee00098

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_SE_T_XSR | 0 | 5 | 0x0000003f | 0xffffffc0 |  |
| SD_SE_T_RTP | 8 | 10 | 0x00000700 | 0xfffff8ff |  |
| SD_SE_T_FAW | 12 | 17 | 0x0003f000 | 0xfffc0fff |  |
| SD_SE_RL | 20 | 25 | 0x03f00000 | 0xfc0fffff |  |
| SD_SE_RL_EN | 28 | 28 | 0x10000000 | 0xefffffff |  |

###SD_STALL
 Address: 0x7ee000a0

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_STALL_CYCLES | 0 | 9 | 0x000003ff | 0xfffffc00 |  |

###SD_SF
 Address: 0x7ee000b4

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_SF_MDLL_CAL | 0 | 8 | 0x000001ff | 0xfffffe00 |  |
| SD_SF_POWSAV_T | 9 | 18 | 0x0007fe00 | 0xfff801ff |  |
| SD_SF_PGEHLD_T | 19 | 28 | 0x1ff80000 | 0xe007ffff |  |
| SD_SF_PHYHOLD | 29 | 29 | 0x20000000 | 0xdfffffff |  |

###SD_CARCRC
 Address: 0x7ee00100

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_CARCRC_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_CARCRC_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DMRCRC0
 Address: 0x7ee00104

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DMRCRC0_LOW | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DMRCRC0_HIGH | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DMRCRC1
 Address: 0x7ee00108

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DMRCRC1_LOW | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DMRCRC1_HIGH | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC0
 Address: 0x7ee0010c

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC0_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC0_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC1
 Address: 0x7ee00110

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC1_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC1_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC2
 Address: 0x7ee00114

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC2_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC2_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC3
 Address: 0x7ee00118

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC3_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC3_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC4
 Address: 0x7ee0011c

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC4_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC4_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC5
 Address: 0x7ee00120

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC5_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC5_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC6
 Address: 0x7ee00124

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC6_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC6_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC7
 Address: 0x7ee00128

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC7_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC7_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC8
 Address: 0x7ee0012c

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC8_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC8_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC9
 Address: 0x7ee00130

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC9_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC9_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC10
 Address: 0x7ee00134

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC10_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC10_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC11
 Address: 0x7ee00138

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC11_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC11_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC12
 Address: 0x7ee0013c

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC12_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC12_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC13
 Address: 0x7ee00140

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC13_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC13_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC14
 Address: 0x7ee00144

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC14_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC14_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQRCRC15
 Address: 0x7ee00148

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQRCRC15_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQRCRC15_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC0
 Address: 0x7ee0014c

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC0_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC0_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC1
 Address: 0x7ee00150

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC1_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC1_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC2
 Address: 0x7ee00154

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC2_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC2_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC3
 Address: 0x7ee00158

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC3_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC3_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC4
 Address: 0x7ee0015c

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC4_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC4_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC5
 Address: 0x7ee00160

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC5_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC5_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC6
 Address: 0x7ee00164

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC6_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC6_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC7
 Address: 0x7ee00168

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC7_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC7_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC8
 Address: 0x7ee0016c

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC8_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC8_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC9
 Address: 0x7ee00170

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC9_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC9_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC10
 Address: 0x7ee00174

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC10_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC10_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC11
 Address: 0x7ee00178

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC11_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC11_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC12
 Address: 0x7ee0017c

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC12_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC12_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC13
 Address: 0x7ee00180

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC13_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC13_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC14
 Address: 0x7ee00184

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC14_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC14_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |

###SD_DQLCRC15
 Address: 0x7ee00188

| field_name | start_bit | end_bit | set | clear | reset |
| --- | --- | --- | --- | --- | --- |
| SD_DQLCRC15_FALL | 0 | 15 | 0x0000ffff | 0xffff0000 |  |
| SD_DQLCRC15_RISE | 16 | 31 | 0xffff0000 | 0x0000ffff |  |