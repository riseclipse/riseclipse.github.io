# RiseClipse downloads

![Logo RiseClipe](img/small_logo_riseclipse.png)

## Validator for IEC 61850 SCL 2003 (version 1.1.0 a22 - 1 October 2021, a Java 8 JRE is required)
This validator can use OCL and NSD files. This is « Work In Progress » because NSD support is incomplete (NOT IMPLEMENTED messages are sometimes displayed).

### Validator for a command line use
* Download [this jar file](downloads/RiseClipseValidatorSCL-1.1.0-a22.jar) somewhere
* Use it (java -jar RiseClipseValidatorSCL-1.1.0-a22.jar) in a Terminal/Cmd window; the command line arguments are given in a usage message. More details on [command lines](commandLineHelp) to use
* OCL files for SCL are available in [this archive](downloads/SCL_OCL.zip); the latest version are available in [this repository](https://github.com/riseclipse/riseclipse-ocl-constraints-scl2003)
* NSD files are are available in [this archive](downloads/NSD.zip); the latest version are available on [the IEC site](https://www.iec.ch/dyn/www/f?p=103:227:502877425777072::::FSP_ORG_ID,FSP_LANG_ID:1273,25)

### Validator with a graphical user interface
* Download and unzip [this archive](downloads/RiseClipseValidatorSCLApplication-1.1.0-a22.zip) somewhere
* It includes updated OCL files and IEC_61850-7-x 2007b and IEC_61850-8-1_2003 NSD files
* Launch the jar (use the BAT file on Windows)
* Add one or more SCL files using the button in the "SCL Files" tab
* Optionally uncheck some OCL constraints in the "OCL Files" tab
* Start the validation using the Validate button in the "SCL Files" tab
* A new Window will appeared with one general tab and one for each SCL file

## OCL Validators for ENTSO-E CGMES v2.4.15 (version 1.0.1 - 8 June 2018, a Java 8 JRE is required)
### Validator for a command line use
* Download [this jar file](downloads/RiseClipseEntsoeCim16Validator-1.0.1.jar) somewhere
* Use it (java -jar RiseClipseEntsoeCim16Validator-1.0.1.jar) in a Terminal/Cmd window; the command line arguments are given in a usage message
* OCL files for CGMES are available [in this archive](downloads/CGMES_OCL.zip)

### Validator with a graphical user interface
* Download and unzip [this archive](downloads/RiseClipseEntsoeCim16ValidatorApplication-1.0.1.zip) somewhere
* Launch the jar (use the BAT file on Windows)
* Add one or more CGMES files using the button in the "CGMES Files" tab
* Optionally uncheck some OCL constraints in the "OCL Files" tab
* Start the validation using the Validate button in the "CGMES Files" tab
* A new Window will appeared with one general tab and one for each CGMES file

