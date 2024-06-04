# RiseClipse command line help for SCL validation jar

![Logo RiseClipe](img/small_logo_riseclipse.png)

## Help for using the command lines

    % java -jar RiseClipseValidatorSCL-1.2.7.jar --help
    INFO    : Copyright (c) 2016-2024 CentraleSupélec & EDF.
    INFO    : All rights reserved. This program and the accompanying materials
    INFO    : are made available under the terms of the Eclipse Public License v2.0
    INFO    : which accompanies this distribution, and is available at
    INFO    : https://www.eclipse.org/legal/epl-v20.html
    INFO    :
    INFO    : This tool is part of RiseClipse.
    INFO    : Contributors:
    INFO    :     Computer Science Department, CentraleSupélec
    INFO    :     EDF R&D
    INFO    : Contacts:
    INFO    :     dominique.marcadet@centralesupelec.fr
    INFO    :     aurelie.dehouck-neveu@edf.fr
    INFO    : Web site:
    INFO    :     https://riseclipse.github.io/
    INFO    :
    INFO    : RiseClipseValidatorSCL version: 1.2.7 (16 May 2024)
    INFO    :
    INFO    : java -jar RiseClipseValidatorSCL.jar option* file*
    INFO    : 	Directories are searched recursively,
    INFO    : 	Files ending with ".ocl" are considered OCL files,
    INFO    : 	files ending with ".nsd" are considered NS files,
    INFO    : 	files ending with ".snsd" are considered ServiceNS files,
    INFO    : 	files ending with ".AppNS" are considered ApplicableServiceNS files (at most one should be given),
    INFO    : 	files ending with ".nsdoc" are considered NSDoc files,
    INFO    : 	files ending with ".zip" are decompressed and each file inside is taken into account,
    INFO    : 	case is ignored for all these extensions,
    INFO    : 	all others are considered SCL files.
    INFO    :
    INFO    : The following options are recognized:
    INFO    : 	--error
    INFO    : 	--warning
    INFO    : 	--notice
    INFO    : 	--info
    INFO    : 	--debug
    INFO    : 		The amount of messages displayed is chosen according to this option, default is --warning.
    INFO    : 	--output <file>
    INFO    : 		messages are outputed in the given file.
    INFO    : 	--xml-schema <file>
    INFO    : 		A preliminary XML validation is done against the given XML schema file.
    INFO    : 	--format-string <format-string>
    INFO    : 		messages are outputed with a java.util.Formatter using the given format string,
    INFO    : 		1$ is severity, 2$ is category, 3$ is line number, 4$ is message, 5$ is filename,
    INFO    : 		6$ is color start, 7$ is color end (these last two are only used if the --use-color option is active),
    INFO    : 		default is '%6$s%1$-7s%7$s: [%2$s] %4$s (%5$s:%3$d)'.
    INFO    : 	--use-color
    INFO    : 		colors (using ANSI escape sequences) are used when displaying messages.
    INFO    : 	--make-explicit-links
    INFO    : 		Implicit links in SCL files are made explicit, this is usually needed for complete validation.
    INFO    : 		Warnings are displayed when problems are detected. Infos are displayed about explicit links being made.
    INFO    : 		Verbosity is about how explicit links are made.
    INFO    : 	--display-nsd-messages
    INFO    : 		Only errors detected in NSD files are displayed by default.
    INFO    : 		This option allows for other messages to be displayed (according to the chosen level).
    INFO    : 	--do-not-display-copyright
    INFO    : 		The tool information is not displayed at the beginning.
    INFO    : 	--use-filenames-starting-with-dot
    INFO    : 		Files whose name begins with a dot are not ignored.
    INFO    : 	--use-different-exit-codes
    INFO    : 		Normal exit code of validator is 1 if there is any validation error, 0 otherwise.
    INFO    : 		If this option is used, exit code is 1 if there is any validation error,
    INFO    : 		2 if there is any warning but no error, 3 if there is any notice message but no warning or error,
    INFO    : 		4 if there is any info message but no notice or warning or error, 0 otherwise.
    INFO    : 	--help-environment
    INFO    : 		Environment variables used are displayed.            
Without the `--output` option, messages are written to the standard output, therefore redirection, using `>fileName.txt` 
at the end of the command line is also possible.
            
   ## Example of use
   
    java -jar RiseClipseValidatorSCL-1.2.7.jar --make-explicit-links fileToValidate.icd OCL NSD >Result.txt

   
