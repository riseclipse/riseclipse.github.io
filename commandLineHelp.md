# RiseClipse command line help for SCL validation jar

![Logo RiseClipe](img/small_logo_riseclipse.png)

## Help for using the command lines

    java -jar RiseClipseValidatorSCL.jar option* file*
    	Directories are searched recursively,
    	Files ending with ".ocl" are considered OCL files,
    	files ending with ".nsd" are considered NS files,
    	files ending with ".snsd" are considered ServiceNS files,
    	files ending with ".AppNS" are considered ApplicableServiceNS files (at most one should be given),
    	files ending with ".nsdoc" are considered NSDoc files,
    	case is ignored for all these extensions,
    	all others are considered SCL files.

    The following options are recognized:
    	--verbose
    	--info
    	--warning
    	--error
    		The amount of messages displayed is chosen according to this option, default is --warning.
    	--output <file>
    		messages are outputed in the given file
    	--xml-schema <file>
    		A preliminary XML validation is done against the given XML schema file
    	--use-color
    		colors (using ANSI escape sequences) are used on message prefixes.
    	--make-explicit-links
    		Implicit links in SCL files are made explicit, this is usually needed for complete validation. Warnings are displayed when problems are detected. Infos are displayed about explicit links being made. Verbosity is about how explicit links are made.
    	--display-nsd-messages
    		Only errors detected in NSD files are displayed by default. This option allows for other messages to be displayed (according to the chosen level).
    	--do-not-display-copyright
    		The tool information is not displayed at the beginning.
    	--use-filenames-starting-with-dot
    		Files whose name begins with a dot are not ignored.
    	--help-environment
    		Environment variables used are displayed.
            
Without the `--output` option, messages are written to the standard output, therefore redirection, using `>fileName.txt` 
at the end of the command line is also possible.
            
   ## Example of use
   
    java -jar RiseClipseValidatorSCL-1.1.0-a23.jar --make-explicit-links fileToValidate.icd OCL NSD >Result.txt

   