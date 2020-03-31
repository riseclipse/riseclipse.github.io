# RiseClipse: using MDE tools for IEC standards

## RiseClipse summary

RiseClipse is an umbrella name for tools based on MDE technologies and dedicated to IEC standards. Open source RiseClipse components are availble under the EPL version 2.0. 

The main use of RiseClipse is to validate IEC CIM files and IEC 61850 SCL configuration files : data described in these files are loaded in a way to become conformant with an UML model (either the CIM UML model or the SCL one), and OCL is used for validation. Therefore, the validation is not only done at the syntactic level but also at the semantic one. See [this article](https://pscc-central.epfl.ch/repo/papers/2016/411.pdf) for a longer explanation.

## RiseClipse developers

RiseClipse is currently developed by the computer science department of [CentraleSupélec](https://www.centralesupelec.fr) and by the MIRE department of [EDF R&D](https://www.edf.fr/en/the-edf-group/who-we-are/activities/research-and-development). This collaboration is done in the context of the [RISEGrid Institute](https://www.centralesupelec.fr/fr/risegrid-institute-research-institute-smarter-electric-grids).

## RiseClipse usage

* The simplest solution to validate CIM and SCL files is to use the [web site provided by EDF](https://rise-clipse.pam-retd.fr/).
* You can also download « fat jar » tools (either with a command line interface or with a simplified graphical user interface) available on [this page](https://wdi.centralesupelec.fr/software/RiseClipse/Downloads). A Java 8 JRE is required to run them.
* Another option (only for SCL files for the moment) is to use a [docker image](https://hub.docker.com/r/riseclipse/riseclipse-validator-scl).
* For more technical usages, see below.


## Acronyms with links

* CIM : [Comon Information Model](https://en.wikipedia.org/wiki/Common_Information_Model_(electricity))
* EPL : [Eclipse Public License](https://www.eclipse.org/legal/epl-2.0/)
* IEC : [International Electrotechnical Commission](https://www.iec.ch)
* MDE : [Model Driven Engineering](https://en.wikipedia.org/wiki/Model-driven_engineering)
* OCL : [Object Constraint Language](https://en.wikipedia.org/wiki/Object_Constraint_Language)
* SCL : [Substation Configuration language](https://en.wikipedia.org/wiki/Substation_Configuration_Language)
* UML : [Unified Modeling Language](https://en.wikipedia.org/wiki/Unified_Modeling_Language)
