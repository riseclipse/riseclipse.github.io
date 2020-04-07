# RiseClipse history

The collaboration on the [CIM](https://en.wikipedia.org/wiki/Common_Information_Model_(electricity)) standard 
between the computer science department of [Supélec](https://fr.wikipedia.org/wiki/École_supérieure_d%27électricité) 
(now [CentraleSupélec](http://www.centralesupelec.fr/)) and the 
MIRE department of [EDF R&D](https://www.edf.fr/en/the-edf-group/who-we-are/activities/research-and-development) 
started in 2002. The CIM was then edited using the Rose tool from Rational. The objective of 
the collaboration was to generate a C++ framework from the Rose model. This framework was able to read and to write files 
conforming to the CIMXML format, and to allow for manipulation of C++ object corresponding to the CIM objects. This 
framework was used to develop converters between closed formats and CIMXML format.

The idea of applying tools of the [EMF framework](https://www.eclipse.org/modeling/emf/) of Eclipse to the CIM was 
raised in 2008. By promoting the CIM from the 
M1 level (UML model) to the M2 level (Ecore model), it was possible to use the OCL Eclipse plugin to check CIMXML files 
without being limited by the XML nature of these files. The tool was called CimClipse and 
[presented](https://cimug.ucaiug.org/Meetings/Milan2010/Presentations/23b%20MTEI%20WG%20CimClipse.pdf) 
at the [CIMug](http://www.cimug.org/) meeting 
in 2010 at Milan. The tool was also used in [Entsoe](https://www.entsoe.eu/) tests in 2010 and 2011.
The **RiseClipse** name was chosen in 2013 because we decided to apply the same approach to another standard (IEC61850), so 
we have to remove CIM in the name. The launch of the 
[RISEGrid Institute](http://www.centralesupelec.fr/fr/risegrid-institute-research-institute-smarter-electric-grids) 
in December 2012 give us the opportunity for the new name.

RiseClipse has been used during the IEC 61850 interoperability tests in September 2015 and September 2019, 
and in the Entsoe tests in July 2016.

RiseClipse has been [presented](https://wdi.centralesupelec.fr/software/downloads/RiseClipse/PresentationPSCC2016.pdf) 
at the [19th Power Systems Computation Conference](http://www.pscc2016.net/) in June 2016 in Genoa. The full 
article is available [here](https://pscc-central.epfl.ch/repo/papers/2016/411.pdf).

# Contributors to RiseClipse

Each year, since 2008, some students from CentraleSupélec, thanks to [EDF R&D](https://www.edf.fr/en/the-edf-group/who-we-are/activities/research-and-development), contribute to RiseClipse (and to CimClipse before) as part 
of their curriculum. 
* 2019-20: Hui Shan Soon & Nora Hechelef (UML for 61850), Elise Moris & Nicolas Baouaya-Moulomba (automatic transformations 
from model updates), Freddy Chung & Kouroche Mazaheri (time and data changes)
* 2018-19: Pedro Donini Linan & Grégoire Carrere-Gee (NSD4RiseClipse), Nicolas David & Jeremy Benzakein 
(CIM – 61850 Harmonisation)
* 2017-18: Julien Hemery & Chloé Mercier (OptimRiseClipse), Eugène Nélou & Benoit Picard--Bellance (Zest4RiseClipse), 
Camille Echelard & Hippolyte Henry (WebClient4RiseClipse)
* 2016-17: Edouard Lejosne & Antoine Rabany (DevOps4RiseClipse), Loïc Mariez & Georges Semaan (Compare4RiseClipse), 
Louis Annabi & Rémi Monnot & Martin Teulon (CDO4RiseClipse)
* 2015-16: Valentin Nicolet & Jean-Baptiste Rocher (NewTypes4OCL), Yin Zhan & Zeliang Yin (RiseClipse4CDPSM), 
Nicolas Miret & Héloïse Parein (RiseClipse4Nuclear)
* 2015: Marjolaine Farré (OCL constraints for SCL)
* 2014-15: Pascal Granier & Alexandre Moureaux (Modsarus2OCL), Quentin Plazar & Ludovic Traniello (Model4SCL), 
Robin Goibert & Florent Feneuil (RiseClipse4Hydro)
* 2013-14: Guillaume Richard & Kaourintin Le Guiban (IEC61850), Loïs Bayssieres & Éric Chantreau (dynamic model)
* 2013: Pierre-Etienne Fiole (displaying networks using Zest)
* 2012-13: Christophe Fauquet & Adrien Piquerez (automatic diagram layout), Camille Bourgaux & Marouan El Mahjoub 
(CimClipse for MSite)
* 2011-12: Jonathan Coueraud & Jérémy Fuhrmann & Marie-Noëlle Lepers (diagram layout profile), Martin Bastie & Denis Baheux 
(profiles support)
* 2010-11: Pape Dieng & Antoine Ladiel (incremental mode support), Gilles Duboscq & Samuel Soubeyran (CIM-Modelica)
* 2009-10: Olivier Dacre-Wright & Hamza Kharbachi (CimXml), Antoine Izsak & Arnaud Massard (CIM messages)
* 2008-09: Kaï Chu & Gaël Rico (CimClipse)
