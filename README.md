# Argon-ONE-NVMe Firmware Update
Repository of Argon ONE M.2 NVMe related updates and configurations

## STEPS to UPDATE the firmware of your Argon ONE M.2 NVMe Expansion Board
**Please follow the instructions properly in order to avoid bricking your unit**

1. DOWNLOAD the **ASMEDIA Configuation Tool ASM2360** into your Windows PC via link below:
    (https://github.com/Argon40Tech/Argon-ONE-NVMe-Firmware/blob/main/ASM236xMPTool_v1.0.0.8.zip)
    
2. DOWNLOAD the **lastest Argon ONE M.2 NVMe Firmware** via the link below:
    (https://github.com/Argon40Tech/Argon-ONE-NVMe-Firmware/blob/main/AS_PCIE_200811_81_00_00.bin)

3. CONNECT your **Argon ONE M.2 NVMe Expansion Board** to your PC via USB (PC - USB 3.0 Cable - NVMe Board)

4. RUN the **ASMEDIA Configuation Tool ASM2360** .exe file on your PC

5. INPUT the following **Configurations into the Tool:**

        a. KEY:             asmedia
      
        b. VENDOR ID:       174C
      
        c. PRODUCT ID:      2362
      
        d. DEVICE REVISION: 0100
      
        e. DEVICE CONFIGURATION SERIAL NUMBER:  000000000F02
     ### ### 
      
        f. S/N CHK HEX - Select this setting
      
        g. S/N Increase - Select this setting (HEX)
      
        h. Update FW - Select this setting
      
        i. Reload FW - Select this setting
     ### ###
      
        j. EPO M.String:    Gen2 10GBps
      
        k. T10 M.String:    Argon
      
        l. T10 P.String:    Forty
      
      
6. LINK In the **FW Browser:** select the path to your firmware file (**lastest Argon ONE M.2 NVMe Firmware**)

7. **Make sure that the Device is Recognized before proceeding.**

8. Once all the configuration are setup, **CLICK** the play button and the bottom left corner of the Tool.

9. The **PROGRESS BAR** will confirm with a **PASS** if your update is **successful.**


      
      
