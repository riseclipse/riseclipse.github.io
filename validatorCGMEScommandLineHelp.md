# RiseClipse command line help for CGMES validation jar

![Logo RiseClipe](img/small_logo_riseclipse.png)

## Help for using the command lines

    % java -jar RiseClipseValidatorCGMES3-1.0.1.jar --help
    INFO: Copyright (c) 2022 CentraleSupélec & EDF.
    INFO: All rights reserved. This program and the accompanying materials
    INFO: are made available under the terms of the Eclipse Public License v2.0
    INFO: which accompanies this distribution, and is available at
    INFO: https://www.eclipse.org/legal/epl-v20.html
    INFO:
    INFO: This tool is part of RiseClipse.
    INFO: Contributors:
    INFO:     Computer Science Department, CentraleSupélec
    INFO:     EDF R&D
    INFO: Contacts:
    INFO:     dominique.marcadet@centralesupelec.fr
    INFO:     aurelie.dehouck-neveu@edf.fr
    INFO: Web site:
    INFO:     https://riseclipse.github.io/
    INFO:
    INFO: RiseClipseValidatorCGMES3 version: 1.0.1 (13 May 2022)
    INFO:
    INFO: usage: RiseClipseValidatorCGMES
    INFO:    --debug                          display all messages
    INFO:    --error                          display only error messages
    INFO:    --format-string <format>         messages are outputed with a java.util.Formatter using the given format string,1$ is
    INFO:                                     severity, 2$ is category, 3$ is line number, 4$ is message, 5$ is filename,6$ is
    INFO:                                     color start, 7$ is color end (these last two are only used if the --use-color option
    INFO:                                     is active),default is '%6$s%1$-7s%7$s: [%2$s] %4$s (%5$s:%3$d)'.
    INFO: -h,--help-environment               display environment variables used
    INFO:    --info                           display info, notice, warning and error messages
    INFO:    --merge                          all ENTSO-E CGMES v3.0.0 files are merged before OCL validation
    INFO:    --notice                         display notice, warning and error messages
    INFO: -o,--output <file>                  all messages are written to the given file
    INFO:    --use-color                      colors (using ANSI escape sequences) are used when displaying messages
    INFO:    --use-filenames-starting-with-dotfiles whose name begins with a dot are not ignored
    INFO:    --warning                        display warning and error messages
            
Without the `--output` option, messages are written to the standard output, therefore redirection, using `>fileName.txt` 
at the end of the command line is also possible.
            
   ## Example of use
   
    java -jar RiseClipseValidatorCGMES3-1.0.1.jar --merge MicroGid-BaseCase/MicroGrid-BaseCase-Merged.zip OCL >Result.txt

   
