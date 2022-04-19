# RiseClipse downloads

![Logo RiseClipe](img/small_logo_riseclipse.png)

## Validator for IEC 61850 SCL 2003 (a Java runtime - at least version 11 - is required)
This validator can use OCL and NSD files. It is « Work In Progress » because NSD support is incomplete (NOT IMPLEMENTED messages are sometimes displayed).

### Validator for a command line use
* Download the latest released `RiseClipseValidatorSCL-x.y.z.jar` [from this repository](https://github.com/riseclipse/riseclipse-validator-scl2003/releases)
* Use it (`java -jar RiseClipseValidatorSCL-x.y.z.jar`) in a Terminal/Cmd window; the command line arguments are given in a usage message. More details on [command line options](validatorSCLcommandLineHelp.md).
* OCL files for SCL are available in [this archive](downloads/SCL_OCL.zip); the latest RiseClipse versions are available in [this repository](https://github.com/riseclipse/riseclipse-ocl-constraints-scl2003).
* NSD files are are available in [this archive](downloads/NSD.zip); the latest public IEC versions are available on [the IEC site](https://www.iec.ch/dyn/www/f?p=103:227:502877425777072::::FSP_ORG_ID,FSP_LANG_ID:1273,25).

### Validator with a graphical user interface
* Download the latest released `RiseClipseValidatorSCLApplication-x.y.z.jar` [from this repository](https://github.com/riseclipse/riseclipse-validator-scl2003/releases).
* OCL (resp: NSD) files are expected to be in an `OCL` (resp: `NSD`) folder at the same level as the jar file; sub-folders can be used; see above for getting some.
* Launch the jar.
* Add one or more SCL files using the button in the "SCL Files" tab.
* Optionally uncheck some OCL constraints in the "OCL Files" tab.
* Start the validation using the Validate button in the "SCL Files" tab.
* A new window will appear with one general tab and one for each SCL file.

### Pre-release versions of validators
These versions have added features; they are made available for testing purposes, any feedback is welcome by sending mail to Dominique MARCADET (dominique.marcadet *at* centralesupelec.fr).

#### Namespaces support
* The current version supports only IEC_61850-7 Edition 2.1. This version tries to support 
multiple namespaces, including using both IEC_61850-7-2007A and IEC_61850-7-2007B in the 
same SCL file.
* It is available [here](https://wdi.centralesupelec.fr/software/downloads/RiseClipse/RiseClipseValidatorSCL-1.1.0-a26rc.jar).
* The corresponding NSD files must be given on the command line.

## OCL Validators for ENTSO-E CGMES v2.4.15 (version 1.1.0 a3 - 20 January 2022, a Java runtime - at least version 11 - is required)
### Validator for a command line use
* Download [this jar file](downloads/RiseClipseEntsoeCim16Validator-1.1.0-a3.jar) somewhere.
* Use it (`java -jar RiseClipseValidatorCGMES-1.1.0-a3.jar`) in a Terminal/Cmd window; the command line arguments are given in a usage message.
* OCL files for CGMES are available [in this archive](downloads/CGMES_OCL.zip).

### Validator with a graphical user interface
* Download and unzip [this archive](downloads/RiseClipseValidatorCGMESApplication-1.1.0-a3.zip) somewhere.
* Launch the jar (use the BAT file on Windows).
* Add one or more CGMES files using the button in the "CGMES Files" tab.
* Optionally uncheck some OCL constraints in the "OCL Files" tab.
* Start the validation using the Validate button in the "CGMES Files" tab.
* A new window will appear with one general tab and one for each CGMES file.

