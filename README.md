# Dataverse-Data-Explorer
This stand-alone component is built to complement [The Dataverse Project](http://dataverse.org/) 
It can be run locally on a webserver with the DDI metadata from a open Dataverse datafile.
The only needed parameter is the *uri* of the metadata file. For Example, exploring 
https://dataverse.scholarsportal.info/api/access/datafile/8988/metadata/ddi can be  done by appending the path to the end of the explorer's html file as follows: [https://scholarsportal.github.io/Dataverse-Data-Explorer/?uri=https://dataverse.scholarsportal.info/api/access/datafile/8988/metadata/ddi](https://scholarsportal.github.io/Dataverse-Data-Explorer/?uri=https://dataverse.scholarsportal.info/api/access/datafile/8988/metadata/ddi)

Additional url paramerets are *locale*, for changing the language (either "fr" or "en")
And *key*, for accessing restricted content accessible to your account.

This project has been adapted from [ODESI](odesi.ca) 
