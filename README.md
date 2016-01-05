About
=====

The [Harvard Cetner for International Development] (http://www.hks.harvard.edu/centers/cid) has a really cool website for exploring the complexity of economic trade between countries, [The Atlas of Economic Complexity](http://atlas.cid.harvard.edu/). 

Unforunately, the site can be slow to process the visualizations and relies on Stata to process the data files. 

My fork of this github repository is a personal project to redo the website using open source tools.

Atlas Data
==========

This file contains the information about how to create the Atlas variables from the World Trade Data reported by Centre d’Etudes Prospectives et d’Informations Internationales (CEPII) in the BACI Dataset.

**Step 1.** Download the files from the Database. The URL for the database is:

[http://www.cepii.fr/CEPII/en/bdd_modele/download.asp?id=1](http://www.cepii.fr/CEPII/en/bdd_modele/download.asp?id=1)

To download the data, you need to have the right credentials (i.e., your institution must be a member of UN COMTRADE).In the download page, we usually download the baci92_XXXX.rar where XXXX indicates the year. This program works only for the consecutive years. Save the rar file(s) in a folder.

