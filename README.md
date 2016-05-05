# Islandora-MODS-XML-forms

The Connecticut Digital Archive, CTDA, is a multisite Islandora installation. The CTDA has a mix of presentation and management sites. The majority of presentation sites are used to present information only. In this case, these presentation sites do not have a log in in the Footer Menu. A minority of presentation sites are also used to log in to add and management CTDA participants' content. Management sites are where CTDA participants log in to add and manage their content.  

## The CTDA sites are:
* [CTDA Collections Presentation](http://collections.ctdigitalarchive.org)
* [CTDA Collections Management](http://manage.ctdigitalarchive.org)

* [UConn Archives and Special Collections Presentation](http://archives.lib.uconn.edu)
* [UConn Archives and Special Collections Management] (http://manage.archives.lib.uconn.edu)

* [Connecticut State Library Digital Collections Presentation](http://digitalcollections.ctstatelibrary.org) 
* [Connecticut State Library Management] (http://manage.csl.lib.uconn.edu)
* [Connecticut State Library Stage or Sandbox](http://csl-stage.lib.uconn.edu)

* [Trinity College Library](http://ctcollections.trincoll.edu)
This is both a production presentation and management site.
* [Trinity College Library Stage or Sandbox](http://trincoll-stage.lib.uconn.edu)

* [UConn Libraries Research Data Archive](http://research.lib.uconn.edu)
This is both a production presentation and management site.

* [CTDA Stage or Sandbox](http://ctda-stage.lib.uconn.edu)
This is a sandbox site.

## XML-forms per site and Associations
The name of the site, the name of the XML Form, and the names of the associated content models

* CTDA Collections Management Site
  * CTDA Collection MODS Form: Associated with: CollectionCModel
  * CTDA Item MODS Form: Associated with: sp-audioCModel, sp_basic_image, sp-videoCModel, sp_pdf, compoundCModel, bookCModel, sp_large_image_cmodel, binaryObjectCModel
  * CTDA Newspaper Issue MODS: Associated with: newspaperIssueCM
  * CTDA Newspaper MODS: Associated with: newspaperCModel
  
* UConn Archives and Special Collections Management Site
  * ASC Audio MODS Form: Associated with: sp_audioCModel
  * ASC Book MODS Form: Associated with: bookCModel
  * ASC Collection MODS Form: Associated with: CollectionCModel
  * ASC Image MODS Form: Associated with: sp_basic_image, sp_large_image_cmodel
  * ASC Item MODS Form: Associated with: binaryObjectCModel, compoundCModel
  * ASC Maps MODS Form: Associated with: sp_basic_image, sp_pdf, sp_large_image_cmodel
  * ASC PDF MODS Form: Associated with: sp_pdf
  * ASC Video MODS Form: Associated with: sp-videoCModel
  
* Connecticut State Library Digital Collections Presentation and Management Site
  * CSL Collection MODS Form: Associated with: CollectionCModel
  * CSL Item MODS Form: Associated with: sp-audioCModel, sp_basic_image, sp-videoCModel, sp_pdf, compoundCModel, bookCModel, sp_large_image_cmodel, pageCModel
  * eRegulations: Associated with: binaryObjectCModel
  
* Trinity College Library Presentation and Management Site
  * Trinity Collection MODS Form: Associated with: CollectionCModel
  * Trinity Item MODS Form: Associated with: sp-audioCModel, sp_basic_image, sp-videoCModel, sp_pdf, compoundCModel, bookCModel, sp_large_image_cmodel, binaryObjectCModel, pageCModel

* UConn Libraries Research Data Archive Site
  * Collection Form: Associated with: CollectionCModel
  * Submission Form: Associated with: sp-audioCModel, sp_basic_image, sp-videoCModel, sp_pdf, compoundCModel, bookCModel, sp_large_image_cmodel, binaryObjectCModel

* CTDA Stage or Sandbox Site
  * CTDA MODS Form: sp-audioCModel, sp_basic_image, sp-videoCModel, sp_pdf, compoundCModel, bookCModel, sp_large_image_cmodel, binaryObjectCModel, pageCModel, CollectionCModel

## Taxonomies per site
The name of the site, name of the taxonomy and then the name of the csv file with the terms
If a site is not mentioned, then no taxonomies have been created.

* CTDA Collections Management Site
  * Genres: Genreterms.csv
  * Held By: CTDA_HeldByTerms.csv
  * Rights: CTDA_RightsTerms.csv
  * Roles: RolesTerms.csv
  
* UConn Archives and Special Collections Management Site
  * Media Type: ASC_MediaTypeterms.csv
  * Roles: RolesTerms.csv
  
* Connecticut State Library Presentation and Management Site
  * digitalOrigin: CSL_digitalOriginterms.csv
  * reformattingQuality: CSL_reformatedQualityterms.csv
  
* UConn Libraries Research Data Archive Site
  * Genres: Genreterms.csv
  * Roles: RolesTerms.csv
  
* CTDA Stage or Sandbox Site
  * Genres: Genreterms.csv
  * Roles: RolesTerms.csv
