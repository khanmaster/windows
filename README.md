# Windows 
## Windows trouble shooting commands for hyper v to use docker, k8 etc.
### Hardware assisted virtualization and data execution protection must be enabled in the BIOS
- Enable Hyper V - You can do this by running the following command as administrator. - 
- ``` dism.exe /Online /Enable-Feature:Microsoft-Hyper-V /All ```
- Enable Hypervisor with following command - 
- ``` bcdedit /set hypervisorlaunchtype auto . ```
``` Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All ```

## Run the above command on Powershell as admin and restart the PC
