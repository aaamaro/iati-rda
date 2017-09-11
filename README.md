# IATI-RDA
IATI-RDA (Registry &amp; Data Analyzer)

Author: Alberto Amaro
License: Freeware

Note: This application is not maintained. 

The IATI [International Aid Transparency Initiative](http://www.aidtransparency.net/) technical proposal revolves around two items:

* Definition of the [IATI Standard](http://www.aidtransparency.net/iati-standard) to standardize the activies and organisations metadata required to exchange Cooperation Information in a common and unique format (XML). This standard was approved in Paris in February 2011.
* The creation of a [IATI Registry](http://iatiregistry.org/) as a repository of IATI raw data links. The providers publish the IATI XML files in their own servers and the IATI Registry stores these links together with a basic set of metatada.

IATI-RDA application has been created to help the users to know and download all the IATI Registry information available.

THE CURRENT RELEASE (V1.2) covers the last IATI Schema release 1.03 and the IATI Registry new conditions (new URLs and JSON formats) defined to upload or download information to or from the Registry.

Here the main features:
* Validation of IATI XML files locally saved. It is possible to validate many files with only one click.
![imagen1](/images/IATI_main_window-12.jpg)

* Selection of the Schema File to validate the XML files. This option facilitates the use of future IATI schema releases. Besides, there is a View to show the Entities and Elements hierarchy defined in the Schema.
![imagen2](/images/schema_file_information-12.jpg)

*Utility to connect to the IATI Registry and download XML files or review the publishers information. It is possible to select a subset of the available XML files and the IATI-RDA app will connect to the Publisher Server to download them.
![imagen3](/images/iati_registry_analyzer-12.jpg)

•Additionally in the this new version 1.2, it is possible to double-click on the packages and view all the metadata information:
![imagen3](/images/Package-Metadata-12.jpg)

Due to modifications in the ckan.org API (IATI data repository) is not possible to guarantee the connection with this server.
