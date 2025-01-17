2.9.9 (2019-07-01)

- Make BHL and ReFindIt API uses more reliable (#5944 - @jrdh)
- Allow configuration of species tabs (#5947 - @jrdh)
- Apply toggle setting on page load (#5888 - @jrdh)

2.9.8 (2019-06-02)

- Upgrade to Drupal 7.67

2.9.7 (2019-04-16)

- Fixed overlapping borders in tables (#5863 - @alycejenni)
- Search submits after clicking an autocomplete suggestion (#5869 - @alycejenni)
- Stopped the upload button jumping around (#5871 - @alycejenni)
- Fixed image display issues on species pages slideshows (#5873 - @alycejenni)
- Allow blocks to be added to main content (#5876 - @benscott)
- "Other" added to gender options in biographies (#5879 - @alycejenni)
- Hide Auto label from Admin>Structure (#5880 - @alycejenni)
- View recently opened/closed issues from sidebar (#5887 - @alycejenni)
- Italics tags allowed in biblio titles again (#5898 - @alycejenni)
- Display terms in a fallback language if not defined in current language (#5905 - @alycejenni)
- Autotag's "fields to populate" drop-down items (#5906 - @alycejenni)
- Fixed AJAX error in contact form when Antibot enabled (#5907 - @alycejenni)
- Fixed CSS issues with custom non-view blocks (#5909 - @alycejenni)
- Titles for custom blocks now display (#5910 - @alycejenni)
- Crossbrowser maps fix (#5904 - @benscott)

2.9.6 (2019-02-26)

Replaces Google-based map interfaces and fixes many bugs, including:

- Replace Google-based maps (gm3 module) (@PaulKiddle)
- Character handling in Literature (#5831, #5803) (@benscott)
- Greek letters (#5769) (@benscott)
- Large file uploads (#5763) (@benscott)
- Performance issues (#5743) (@benscott)
- Private groups context indexing (#5699) (@benscott)
- Spam user registration (#5687) (@benscott)
- Scratchpads classification service (#5674) (@benscott)
- Taxonomy tree widget (#5657) (@benscott)
- Docker SOLR replace image (@benscott)
- EOL services access #5688 (@benscott)
- Scratchpad sandbox offline (#5824) (@benscott)
- Scratchpads.eu stats (#5689) (@benscott)
- PHP 7.1 Docker (#5808) (@benscott)

2.9.5 (2019-01-30)

This is a small update that includes a security fix for Drupal core
and also fixes a bug we missed in the PHP 7 work.

- Upgrade to Drupal 7.63 (#5773) (@PaulKiddle)
- Update views_slideshow module (#5792) (@PaulKiddle)


2.9.4 (2019-01-14)

- Upgrade to PHP 7 (#5671) (@PaulKiddle)
- Upgrade to Drupal 7.61 (#5707) (@jrdh)
- Replace Simon with Scratchpads Team in DwC-A metadata (#5712) (@jrdh)
- Strip HTML tags from page titles (#5734) (@jrdh)
- Allow TIF files to be uploaded (#5758) (@jrdh)
- Rotate docker logs (#5761) (@jrdh)
- Fix AJAX responses when using the wavesurfer module (#5764) (@jrdh)
- Wrap biblio URLs to improve presentation (#5765) (@PaulKiddle)

2.9.3 (2018-10-22)

- Upgraded Drupal to 7.60
- Fixed GBIF map tiles
- Allow configuration of upload file size in Docker
- Simplify docker filesystem
- Update bio.acousti.ca modules

2.9.2 (2018-10-03)

- Upgraded Drupal to 7.59
- Added Docker & docker compose
- Issue tracker uses Github issues
- Updated help to use Github Wiki
- Fixed Google Maps
- Removed duplicated legacy modules

2.8.1 (2016-06-17)

- Ecological interactions.

2.8.0.11 (2016-06-01)

- Upgrades to some of the easier contrib modules to check.

2.8.0.10 (2016-06-01)

- Upgrade Drupal
- Fix maps issue
- Update team logins

2.8.0.9 (2015-10-30)

- One last release before I leave (#4477)

2.8.0.8 (2015-10-30)

- Fix an issue with scratchpads_tweaks_cron() caused by new security
  constraints in Drupal 7.40

2.8.0.7 (2015-10-29)

- Upgraded Drupal to 7.41
- Hide the OBOE module (needs removing)
- Minor fix to the Morphbank harvest module

2.8.0.6 (2015-10-21)

- Fix a permissions issue with the Taverna module

2.8.0.5 (2015-10-08)

- Delete JSPhylo temporary files

2.8.0.4 (2015-10-07)

- Allow missing parent menu items (#4468)

2.8.0.3 (2015-10-07)

- Moved the scratchpads_em theme to fix issues with e-monocot sites.

2.8.0.2 (2015-10-07)

- Upgrade the Wavesurfer library
- Update the Taverna module to use Curl

2.8.0.1 (2015-09-24)

- Minor fixes

2.8.0 (2015-09-21)

- Added a tool that allows users to create graphs using views (#4453)
- The map field allows the use of UK grid references (#4452)

- Fixed an issue with the indexing of public/private files (#4360)
- Ensure the GBIF DwC-A is correctly structured for GBIF
- Fixed a minor issue with the e-monocot views module
- Added an index to the eolapi.label field to improve performance
- Moved from our old Solr server to our new one
- Ensure Scratchpads Catalogue of Life module is enabled on all sites
- Update the name of an SPM node if the term it's associated with is updated
  (#4356)

2.7.3.4 (2015-09-17)

- Fix an issue with the GBIF Registry code that resulted in an error on install

2.7.3.3 (2015-09-17)

- Fixed a bug with the bio.acousti.ca site

2.7.3.2 (2015-09-02)

- Code for detecting duplicate Specimen IDs reported false positives

2.7.3.1 (2015-08-28)

- Remove the Scratchpads statistics endpoints from the GBIF registry
- Register datasets with the GBIF registry as Checklists

2.7.3 (2015-08-27)

- Upgrade Drupal to 7.39
- Fix registration with GBIF
- Fixed a minor bug with IUCN (#4442)
- Allow hiding of the Revisions tab by role

2.7.2 (2015-07-28)

- Added caching to drupal_system_listing() and drupal_parse_info_file()
- Upgraded PHPExcel library to 1.8.1
- Added httprl to be used by the advagg module
- Upgraded GBIF registry to work with the real registry
- Register DwC-A endpoints with the GBIF registry
- Register statistics endpoints with the GBIF registry
- Fix the URL link to the EOL API page
- Fix the Species Slideshow so that only big images can be clicked
- Updated the Lucid applet so that it is the signed version
- Removed some hook_requirements() functions to speed up admin pages
- Ensure Slickgrid works correctly on translated sites
- Ensure that the correct term is 'bold' on each taxonomy term page (#4437)

2.7.1.5 (2015-07-09)

- Check the field_langauge of all fields and tweak the values accordingly
  (#4426)

2.7.1.4 (2015-07-08)

- Only convert LANGUAGE_NONE values in node entities (#4426)

2.7.1.3 (2015-07-03)

- Upgraded views_data_export module to 7.x-3.0beta8

2.7.1.2 (2015-07-02)

- Ensure that when rows are skipped in Slickgrid, that the rows are correctly
  indexed (#4416)

2.7.1.1 (2015-07-01)

- Fix a bug with the tag/tagtag module that prevented it from being possible to
  disable tag/autotag altogether
- Ensure the removal of LANGUAGE_NONE values works as expected

2.7.1 (2015-06-30)

- Upgrades: Webform (7.x-4.9), Drupal (7.38)
- Fixed a long standing bug with the handling of translated fields and imported
  data (#1324, #3401, #3657, #4028, #4162, #4332)
- Fixed an issue that resulted in skipped rows in Slickgrid views (#4416)
- Made changes to ensure Scratchpads is compatible with Aegir 7.x-3.x
- Enable 'sup' and 'sub' tags in node titles (#4408)
- Ensure users can create polygons on maps (#4414)
- Enable importing from Catalogue of Life's 2015 checklist

2.7.0.3 (2015-05-15)

- Updated the URL of the Scratchpads Solr instance

2.7.0.2 (2015-05-07)

- We do not want the scratchpads_col module enabled on sites

2.7.0 (2015-05-07)

- Added a module that uses our own Classification Service, which currently
  provides classifications from the Catalogue of Life
  (http://classifications.scratchpads.eu) (#4375)

- Display 255 years in the biblio facet (#4387)
- Fixed the Biblio module again (#4384)
- Format simple taxonomy page titles in the same way as standard taxon pages
- Updated Drupal to 7.37, advagg (7.x-2.8), i18n (7.x-1.12)
- Minor performance improvement for imports
- Field Media no longer required for Specimen/Observation nodes (although it was
  never actually required)

2.6.4.8 (2015-05-05)

- Fix a minor typo in the Excel importer that had a major effect on the import.
  (#4388, 4389, #4393)

2.6.4.7 (2015-04-30)

- Upgraded views to 7.x-3.11

2.6.4.6 (2015-04-29)

- Fixed a typo that resulted in incorrect GUIDs for node reference (GUID)
  columns in the Feeds Excel template (#4366)

2.6.4.5 (2015-04-17)

- Removed GBIF ECat module

2.6.4.4 (2015-04-16)

- Allow users to edit translation strings

2.6.4.3 (2015-04-16)

- Stop the update module from moaning completely

2.6.4.2 (2015-04-15)

- Don't CAPTCHA the user_login and user_login_block forms

2.6.4.1 (2015-04-13)

- Ensure we only filter EOLAPI files out if the EOLAPI module is enabled

2.6.4 (2015-04-13)

- Updated Drupal and many contrib modules
- Hide the updates from our users (#4371)
- Fixed the Sandbox install to ensure images and content are correct (#427)
- Prevent editing of languages by our users, and restore "prefix" to be the same
  as the ID
- Ensure the login block opens on translated pages
- Include values for '{field}:guid' mappings (#4366)
- Fix an issue with the EOL DwC-Archive that resulted in fewer rows than
  expected
- Filter out EOL API files from Grid and Media library views (#4359)
- Ensure remote files work in the media browser
- Allow altering of data to be included in the Feeds XLS template file (by
  altering the query that returns the list of IDs)
- Remove Drush specific code from an update (#4362)
- Ensure Colorbox popups work on translated pages (#4365)
- Correctly set mimetype of EOL API files
- Converted most instances of file_get_contents() to drupal_http_request()
- Patched media module to redirect to home page

2.6.3.8 (2015-04-10)

- Ensure files associated with a gallery more than once can be indexed

2.6.3.7 (2015-04-10)

- Fix an issue with the Tinytax block on multilingual sites

2.6.3.6 (2015-04-08)

- Fix a error that resulted in a redirect to a private file when viewing a
  private file in a media gallery (#4360)

2.6.3.5 (2015-04-07)

- Fix a minor issue with scratchpads_width_and_height that prevented remote
  images from having their widths/heights calculated (#4357)

2.6.3.4 (2015-03-28)

- Performance improvements for remote_stream_wrapper files

2.6.3.3 (2015-03-27)

- Converted most instances of file_get_contents() to drupal_http_request(), and
  ensured a timeout is set for each request.

2.6.3.2 (2015-03-26)

- Ensure all EoL DwC-A rows are returned (#4353)

2.6.3.1 (2015-03-25)

- Fixed an issue that prevented some sites from upgrading to 2.6.3

2.6.3 (2015-03-24)

- Updated NCBI, BHL, IUCN and ReFindit modules to use ajaxblocks module
- Added a timeout to scratchpads_width_and_height to prevent it taking a lot of
  time
- Changed the Solr instance we are using
- Performance improvement for scratchpads_messages loading
- Release of the morphbank_harvest module to Bembidion.info (available to others
  on request, and will be available in a later release following testing)
- Update all file/media fields so they can reference remote images

2.6.2.4 (2015-03-23)

- Prevent scratchpads_width_and_height causing very slow page loads.

2.6.2.3 (2015-03-23)

- Changed the URL to our Solr instance

2.6.2.2 (2015-03-19)

- Security update, updated Drupal to 7.35, Ctools to 7.x-1.7 and Webform to
  7.x-3.23

2.6.2.1 (2015-03-13)

- Fixed an issue with Feeds XLS that prevented more than 49 rows being imported
- Display the title of a linked node for a node reference field (#4161)

2.6.2 (2015-03-12)

- Revert the changes to the CKEditor plugin/module (#4343)
- Ensure users can login and accept T&Cs on offline sites (#4342)

2.6.1.1 (2015-03-10)

- Increase the length of the biblio_keywords field (#4225)

2.6.1 (2015-03-10)

- Altered EOLAPI module so that it does not store full images locally (just
  thumbnails and previews)
- Upgraded memcache module to 7.x-1.5 which will enable us to run memcache
  without the "-I 16M" flag
- Removed unused contrib modules
- Upgraded flag (7.x-2.2), token (7.x-1.6), site_map (7.x-1.2),
  subform (7.x-1.0-alpha2), variable (7.x-2.5), webform (7.x-3.21),
  calendar (7.x-3.5), views_slideshow (7.x-3.1), views_bulk_operations(7.x-3.2),
  imagecache_actions (7.x-1.5), field_group (7.x-1.4), entitycache (7.x-1.2),
  advanced_help (7.x-1.1), weight (7.x-2.4), varnish (7.x-1.0-beta3), oauth
  (7.x-3.2), menu_block (7.x-2.5), linkit (7.x-2.7), link (7.x-1.3), honeypot
  (7.x-1.17), entity (7.x-1.6), countries (7.x-2.3), context (7.x-3.6),
  comment_notify (7.x-1.2), colorbox (7.x-1.6), ctools (7.x-16), captcha
  (7.x-1.2), auto_entitylabel (7.x-1.3), date (7.x-2.8), advagg (7.x-2.7), views
  (7.x-3.10)
- Generate the biblio_dump.bib file much more efficiently, rather than every
  cron run (#4239)
- Created a basic taxonomy statistics module (#4266)
- Prevent access to the updates pages
- Strip metadata from resized images which reduces their size
- Ensure DOI import works as expected (#4328)
- Upgraded CKEditor

2.6.0.10.1 (2015-03-06)

- Improve the scratchpads_statistics_cron function to prevent memory issues and
  possible timeouts (#4239)

2.6.0.10 (2015-03-04)

- Fixes the display of text and application files when attached to nodes (#4321)
- Prevent access to the updates page

2.6.0.9 (2015-03-04)

- Ensure that languagefield fields can be imported into (#4334)

2.6.0.8 (2015-02-26)

- Enable the update module to reflect our usage on Drupal.org

2.6.0.7.1 (2015-02-25)

- Ensure empty cells are not imported into list values (#4338)

2.6.0.7 (2015-02-25)

- Allow searching within literature (#4331)

2.6.0.6 (2015-02-24)

- Ensure that user_reference fields are displayed consistently, and also include
  given names (#4336)

2.6.0.5 (2015-02-24)

- Fixed a bug that prevented GM3 maps from displaying, and possibly also values
  from being saved to GM3 fields (#4333)

2.6.0.4 (2015-02-12)

- Ensure Slickgrid works with the latest Views module (#4326)

2.6.0.3 (2015-02-11)

- Allow the Editor role to add/delete/edit/import taxonomy terms (#4324)

2.6.0.1 (2015-02-09)

- Clean up EOL API files that haven't been successfully moved
- Also fix the aspect ratio of species page images (#1247)

2.6.0 (2015-02-06)

- Updated the EXIF Custom module enabling it for all Scratchpads (#4176)
- Created a simple Entity filter (#4219)
- Greatly improved the translation functionality of Scratchapds (#2317)

- Upgraded Drupal to 7.34
- Enable any block to be embedded on the front page (#1174)
- Hide simplenews settings
- Updated GBIF maps to their new API (v1)
- Ensure the dblog module is always disabled
- Removed called to feeds_alter() which required a patched version of feeds
- Ensure "0" values are correctly exported (#4004)
- Present images in rows, rather than a single column (#4297)
- Ensure tinytax options take immediate effect (#4305)
- Ensure media views aren't cached to ensure newly uploaded files are visible in
  the media library tab
- Improved and cleaned up the tag/autotag modules, and enabled tag with tips
- Added a reference field to the lexicon term output (#3001)
- Allow the citethispage list of authors to be tweaked. (#3920)
- Added the format option to the WYSIWYG editor (#1000)
- Hide all media with a weight of 100 from ALL media gallery pages. (#4013)
- Don't display empty stripy divs (#4296)
- Allow a user to specify a list of terms that should always be displayed in a
  tinytax tree. Fixes (#4305)
- Reset to alphabetical button added to TUI (#4274)
- Added the ability for a user to clear their site's cache. (#4300)
- Don't automatically enable the CKEditor SCAYT (Spell Check As You Type)
  feature. (#4302)
- Front page views should use the summary if available. (#4284)
- Prevent population of Media (URL) field in Excel templates (#4265)
- Upgraded the mediaelement library and module (#4263)
- Ensure a Slickgrid row can be updated multiple times without waiting for
  caches to clear (#4254)
- Removed calls to eval() to improve overall security
- Display only 50 results on a Biblio page
- Tweaked the ShareThis widget settings to improve performance
- Merged code from various development branches (yet to be fully released)

2.5.5 (2015-01-07)

- Upgrade the DwC-Archiver module

2.5.4.3 (2015-01-02)

- Display the front page images uncropped if desired (#1247)

2.5.4.2 (2014-12-10)

- Fixes an issue with Autotag that prevented saving of content with specific
  diacritic marks (e.g. Baňař). (#4283)

2.5.4.1 (2014-11-20)

- Patched Drupal to include patches from Drupal 7.34

2.5.4 (2014-11-10)

- Added the improved DwC-A Export module. (#4126)

2.5.3.4 (2014-10-24)

- Possibly improve "cold start" times of sites

2.5.3.3 (2014-10-23)

- Prevent clearing of image width and height cache.

2.5.3.2 (2014-10-20)

- Applied patch for https://www.drupal.org/SA-CORE-2014-005

2.5.3.1 (2014-09-15)

- Fix an error that caused "odd" behaviour when importing into a user reference
  field by name (#4226)

2.5.3 (2014-08-14)

- Delete unpublished anonymous forum nodes older than one week (likely to be
  spam)
- Ensure responsive images are still responsive
- Aggregate the species map view (#4210, #2461)
- Allow the updating of a WoRMS imported classification (#4205)
- Prevent half created terms (those that failed before creating the revision)
  from blocking the creation of additional terms (#4208)
- Add an error message to the WoRMS service for failed downloads
- Fix an error that could result in duplicate UUIDs from the Taxonomy Editor
- Allow more than 1024 chars in a taxonomy autocomplete field (#4195)

2.5.2.3 (2014-07-24)

- Try and ensure that the WoRMS service does not timeout (#4199)

2.5.2.2 (2014-07-22)

- Prevent caching of all species page blocks (#4202)

2.5.2.1 (2014-07-22)

- Prevent caching of species nomenclature block (#4202)

2.5.2 (2014-07-15)

- Added .gz to list of allowed extensions (#4194)
- Removed the emails sent to the Scratchpads team
- Ensure that taxonomy fields associated with multiple vocabularies don't mess
  up the validation formula and PermittedValues worksheet. (#4184)
- Only use "identify" command for files with specific extensions.  This is to
  ensure identify doesn't get used to try to identify very large video or audio
  files. (#3310)
- Updated Google Analytics .myspecies.info code
- Don't enable views caching on Publication views
- Allow importing of "0" into any field provided by the number module (#4004)
- Display coordinates when clicking on a point (#4159)
- Allow the select other field to work with the Tag API (#4166)
- Link the main image on the front page to its entity page (#4163)
- Clean up failed batches and TCS downloads
- Ensure filtering by filename hits files with upper case extensions (#4158)
- Allow altering the author of a node on import (#4143)
- Prevent "ghost" galleries from being displayed (#4155)
- Improved caching, which should improve the performance of sites

2.5.1.3 (2014-06-26)

- Fix a bug introduced in 2.5.1 (#4173)

2.5.1.2 (2014-06-16)

- Ensure GM3 fields render correctly (#4152)

2.5.1.1 (2014-06-13)

- Tweak the .htaccess file for the AdvAgg module

2.5.1 (2014-06-13)

- Fix a bug with Google Maps that prevented wide area points from displaying
  (#4150)
- Page results with large numbers of authors don't break the citation module
  (#4150)
- Various updates to the publication module
- AJAX/AHAH forms don't break CAPTCHA (#4147)
- Allow map fields to be added to the user entity/bundle
- Force update of taxonomy terms on ALL imports (no matter if data appears to
  have changed) (#4142)
- Allow "0" to be imported into text fields (#4004)
- Link to the importer page updated
- Enable the AdvAgg module to improve CSS and JS aggregation (#4101)
- Ensure sorting of Tinytax and TUI are ordered by weight (#4134)
- Try to prevent redirection loops (#4128)
- Dynamically set the resolution of the GBIF layer based on zoom
- Link to the results page of ReFindIt (#4105)
- Fix formatting of inline citations on taxon pages (#4118)

2.5.0.1 (2014-05-08)

- Updated the EoL/GBIF maps layer module to use the GBIF service (EoL have
  pulled theirs). (#4117)

2.5.0 (2014-05-07)

- Enable the revisioning of taxonomy terms (#3892)
- Replace Google Scholar module with ReFindit (#4105, #1174)

- Improve sorting of Biblio pages (#4110)
- Prevent <i> or <em> tags being presented on Scratchpads pages in the Issues...
  block (#4113)
- Fixed an issue with multiple taxonomy fields on biblio nodes (#4099)
- Minor presentation tweak (#3884)
- Aggregate slickgrid views on taxonomy pages (#4082)

2.4.1.2 (2014-04-22)

- Prevent a WSOD on some pages with facets. (#4097)

2.4.1.2 (2014-04-04)

- Ensure TUI allows a term to be moved to the root of a tree. (#4084)

2.4.1.1 (2014-04-03)

- Prevent taxonomic name terms from displaying in the terms facet (#4081)

2.4.1 (2014-04-03)

- Delete temporary files older than one month to free up valuable disk space
- Ensure description fields on files are imported as Filtered HTML, rather than
  plain text (#4076)
- Allow importing from CSV files (#4058)
- Display the GID of a group on the group edit page, and allow importing into a
  group (#4065)
- Repatched feeds_alter() to ensure alter functions happen in the correct order.
- Only display author names with references associated in facet autocomplete
  search box (#4057)
- Ensure menu tabs are correctly translated (#4063)
- Correctly import dates from Excel (no longer need to ensure that text is
  correctly formatted)
- Added Bigmenu as a tool (#3383)
- Allow access to the advanced help popup (#4044)
- Ensure the nomenclature block displays as expected (#3890)
- Prevent the editing of some views by users
- Delete entries from the feeds_item table with blank GUIDs (#4020, #4022)
- Export boolean values (#4004)
- Ensure the emonocot citation block is not cached (#4008)
- Some minor code fixes

2.4.0.2 (2014-03-27)

- Prevent field_group_info_groups() from clearing ctools caches and prevent
  further errors(#4026, #4029, #4030, #4061)

2.4.0.1 (2014-03-18)

- Prevent field_group_info_groups() from clearing ctools caches (#4026, #4029,
  #4030)

2.4.0 (2014-03-06)

- Enable the use of a private file system (#909)

- Ensure taxonomy terms are available to search for the anonymous user (#3919)
- Add roles and permissions to Groups (#3961)
- Fix e-monocot portal feedback (#3465)
- Hide WCM ID field from nomenclature block (#2885)
- Fix and improve Slickgrid (#3992, #3899, #3896, #3713, #3231, #1317)
- Reduce the number of PHP errors, and log errors to syslog rather than the DB
- Ensure the entityconnectpreview module is enabled (#1297)
- Fix an issue on e-monocot sites that could prevent the synonyms tab from being
  displayed
- Enable a user to request a full site backup from Aegir (#2830)
- Enable bulk assigning of users to groups (#3443)
- Fix an issue on some migrated sites that prevents editing of user reference
  fields (#3430)
- Sort Solr search pages by creation date descending (#3963)
- Prevent orphaned terms appearing in autocomplete boxes (#3933)
- Prevent a Feeds template error (#3960)
- Possibly fix importing large numbers of terms from WoRMS (#3932)
- Flag up inactive Scratchpads, and mail users if they've never logged in
- Improve performance of the taxonomy formatter (#3080)
- Prevent the taxonomy editor from orphaning terms (#1436)
- Allow deletion of multiple terms in the taxonomy editor (#2900)
- Aggregate data on taxon pages (#2461)
- Sort fields in the Excel templates (#1977)
- Increase the sensitivity when dragging terms in the taxonomy editor (#2289)
- No longer use a jQuery CDN
- Delete EOL temp files (#3888)
- Fix an issue with the Biblio export links (#3889)
- Prevent taxon page headers from being displayed full div height (#3891)
- Display only relevant type specimens in the nomenclature block (#3890, #3714)
- Link images to their file entity to enable the popup (#3864)
- Prevent all images being resized then "narrow" version of the front page
  (#3866)
- Hide Group roles and permissions (#3865)
- Hide Vernacular name label if no values are present (#3772)
- Enable the "Remember me" feature if logging in via OpenID
- Upgraded Drupal to 7.26
- Export key files in DwC-A (#2295)
- Sort galleries by weight (#2992)
- Remember the status of the tinytax toggle checkbox between pages (#2343)
- Ensure validation is performed on import (#2208)
- Tag images attached to specimens (#3372)
- Add default weights for all images (#3396)
- Allow certain fields to be added/removed from additional entity/bundles
  (#3178)
- Renamed Moneran to Bacteria/Archaea
- Removed the CAPTCHA After, Mollom and Boost modules
- Display authors when searching by taxonomy (#3790)
- Attempt to export more than 65534 records (#3776)
- Ensure distribution and habitat changes can be saved (#3503)
- Ensure tabs in the Specimens Slickgrid can be switched between (#3747)
- Allow the Tinytax block to be hidden for anonymous users (#3773)

2.3.2.4 (2014-01-16)

- Half of the fix for #3680 which will allow sites to be fixed by clearing their
  caches.

2.3.2.3 (2014-01-14)

- Updated Ed's OpenID

2.3.2.2 (2014-01-09)

- Prevent the user being fooled into thinking a block is going to appear (#3773)

2.3.2.1 (2014-01-08)

- Enable CAPTCHA on Webform forms (#3749)

2.3.2 (2014-01-08)

- Allow exporting of all references from a search, rather than just the first
  100 (#1420)
- Batch the export of specimens to CSV/XML from the Slickgrid table (#3769)
- Add a user and node reference (GUID) column to import templates (#3755, #2487)
- Ensure that GUIDs in imports are GUIDs, and not IDs for a specific import
  (#3731)
- Prevent user 2 from being redirected to the setup work-flow when editing other
  users
- Clean up the user/%uid/edit/%profile form pages
- Enable subscribing of users to newsletters (#3750)
- Ensure that creation of Biblio nodes using a DOI works as expected (#3764)
- Allow setting of whether content in a group is public or private, and a
  general tidy of group permissions (#3721)
- Ensure that terms can always be toggled in Tinytax
- Load Tinytax dynamically, and cache the data in Varnish
- Moved CC images to our own mirror which can be cached by Varnish (actually
  quicker than CC's own server)
- Fix the autocomplete for associating a user with a biblio author (#2954)
- Allow twitter feeds on the front page of a site, and hide the users' twitter
  settings page (#3711)
- Tweaked the default sort order for Slickgrid views (#3199)
- If T&Cs have been tweaked, link to them, otherwise link to the default
  scratchpads.eu page
- Enable adding of media by URL as well as file upload (#867)
- Advise users that deleting a gallery does not delete the images in it (#1099)
- Add a description to the Media field (#1104)
- Allow filtering of the users pages (#3724)
- Remove the confusing HTML option for newsletters (it is not supported) (#3701)

2.3.1.3 (2013-12-17)

- Ensure that the Slickgrid data callback is not cached #3738

2.3.1.2 (2013-12-09)

- Remove a faulty line of code (#3719)

2.3.1.1 (2013-12-06)

- Remove a faulty line of code (#3719)

2.3.1 (2013-12-05)

- Upgraded Drupal to 7.24 (#3495)
- Display a preview of an entity when using the entityconnect widget (#1297)
- Enable importing into a file field using a URL (#1456)
- Clean up the WYSIWYG Media options (#1971)
- Order the Taxonomy search autocomplete (#3679)
- General testing bug fixes (#107)
- Allow the upload of KMZ files (#3673)
- Prevent duplication of tags on biblio nodes (#3657)
- Order of terms in Tinytax/TUI (#3078)
- Ensure taxonomy hierarchies are imported correctly (#3663)
- Remove our use of the term "moneran" (#3638)
- Improved performance of the Tinytax block
- Increased the sensitivity of our spam detection
- Removed a link to GBIF's ECAT (#3645)
- Move to using Varnish, rather than Boost (#3049)
- Italics for series and subseries (#3638)
- Prevent disabling of tools if they're in use (#3635)
- Display unit indicators and names correctly (#3222)
- Display Volume when selecting biblio nodes in an autocomplete field (#3527)
- Bandaged an issue with caching (#3503)
- Use WYSIWYG editor for the Remarks field (#3567)
- Refresh the admin paths when enabling a tool (#3623)

2.3.0.3 (2013-11-08)

- Added IMu library

2.3.0.2 (2013-11-08)

- Added IMu module

2.3.0.1 (2013-11-07)

- Fixed a minor bug with the tools module
- Ensure we do not try to edit an incorrectly cached copy of a node (#3503)
- Cache the language switcher block by page, not role (#3545)

2.3.0 (2013-11-06)

- Added the Publication tool

- Ensure the Groups feature can be complete disabled (#3348)
- Sort groups pages chronologically descending (#3608)
- Various publication module fixes
- Minor Slickgrid fix to allow Slickgrid views to be easily edited
- Allow site maintainers to specify whether anonymous users can post comments
- Prevent the colorbox popup appearing when clicking on view/cancel from the
  delete page (#3533)
- Added the authority name to taxonomy autocomplete boxes to help distinguish
  homonyms (#3527)
- Index most file types, in addition to media (#793)
- Minor performance improvement for large classifications
- Allow "Fields" added to Biblio records to be updated using the Excel importer
- Allow associating content with a file in imports (#3494)
- Ensure required and permitted values are included in templates (#3521)

2.2.0.1 (2013-10-10)

- Ensure the changes to the role_delegation module work as expected (#3448)

2.2.0 (2013-10-09)

- Added the Citations tool (#3130)

- Fixed an issue with the Biography feature (#3473)
- Prevent failed imports from being restarted (#3439)
- Updated to DwC-Archives (#3405, #3400)
- Display the users on three tabs (All/People/Users) (#3285)
- Ensure the Groups feature enables fully (#3330)
- Added the views_date_format_sql module for grouping views by dates (#3492)
- Ensure the XLS templates are created correctly when using multiple application
  servers (#3467)
- Simplify the configuration of site information (all from front page) (#3306)
- Prevent the import of empty strings by feeds (#3237)
- Allow use of regular expressions in Slickgrid filters (#3102)
- Allow sidebar tabs to be as wide as they need to be (#3308)
- Only display the specimens tab when required (#3445)
- Show optgroups for role delegation (#3448)

2.1.10 (2013-09-25)

- Fixed the twitter filter (#3288)
- Fixed an issue with cloned nodes and UUIDs (#3384)
- Display the full reference when hovering over a biblio citation (#3395)
- Improved error message for RefBank import (#3020)
- Enable the hiding of PDF attachments associated with biblio nodes (#3404)
- Tweak the meta.xml file in DwC-A exports (#3400)
- Ensure Darwincore and other modules warn users when being disabled (#3271)
- Clean up a bug with Darwincore when disabled (#3067)
- Reorder facets on search pages (#2244)
- Prevent redirecting of non-admin users when adding certain nodes (#3444)
- Add validation to user/people import (#3374)
- Ensure content type publishing options can be updated (#3433)
- Prevent jumping numbers in certain pagers (#3329)
- Only display the BHL magnifying glass if required (#3093)
- Export TID and Name for a taxonomic name field (#3414)
- Prevent periodic import failures (#3392)
- Prevent the ShareThis widget appearing multiple times on a page (#3284)
- Minor changes to facilitate offline Scratchpads Training courses
- Partial fix for incorrect species occurring in the IUCN box (#3321)
- Prevent a "Missing relationship" warning (#3328)
- Ensure the IUCN and other widgets display correctly (#3385)
- Fixed (#3393, #3402, #3386)

2.1.9.2 (2013-09-24)

- Prevent non-admin users from being redirected to their user page (#3444)

2.1.9.1 (2013-09-13)

- Ensure select text fields can be imported from Excel (#3393)

2.1.9 (2013-09-11)

- Ensure the EOL TCS import works (#3318)
- Export TID rather than name for the Excel template (#3362)
- Various EOL DwC-A fixes
- Display the copyright owner and the licence on the front page slideshow
  (#3105)
- Ensure single value facets display correctly (#3298)
- Fixed a bug with the filter on content views (#3317)
- Ensure all biography fields are exported in the template files (#3370)
- Display 56 media items on gallery pages (#3282)
- Allow specifying by labels for text fields (#3375)
- Fixed an issue that prevented images from being uploaded (#3299)
- Minor fix to the "Make this profile public" option (#3378)
- Display author names even when they can not be parsed (#3365)

2.1.8 (2013-08-28)

- Only include approved comments in DwC-A exports (#3144)
- Added honeypot to help fight spam user account submissions (#3238)
- Weighting option on taxon description pages (#2446)
- User biographies (#3202)
- Biblio citation style settings (#3053)
- Allow People to have login access (#3219)
- Fix image upload issue (#3303)
- Use GBIG taxonomic status values in DwC-A exports (#2406)
- Remove hyperlink from references in DWC-A exports (#3055)
- Remove Group content type when Groups are disabled (#3074)
- Separate media links on node edit form (#1478)
- Prevent duplicate terms from being added to autotag taxonomies (#3236)
- Theme the media browser (#1962)

2.1.7 (2013-08-14)

- Added the tracker module as a tool (#931)
- Ensure that certain configuration pages are hidden
- Added the Spambot and Captcha modules to help prevent spam (#3187)
- Delete any spam comments that may have been received (#3187)
- Display the TID and GUID in the Taxonomy editor (#2878)
- Allow uploading of SVG and TIFF images (#1511)
- Ensure that users can set width/height/align attributes on images (#2852)
- Automatically tag biblio records based on keywords (#2047)
- Allow basic GM3 configuration (#976)
- Performance improvements (#1407)
- Prevent displaying of duplicate references on the taxon page biblio tab
  (#3235)
- Prevent locking of the body field so that it may be removed from content types
- Added a message to the Contact Us form stating that the message is for the
  site maintainer
- Ensure a classification may be exported when the hierarchy is broken
- Display all rights reserved (#2973)
- Cache the Remote Issues Tab to improve performance
- Fixed a display issue with the forum sidebar (#3210)
- Allocate more memory for the Feeds XLS import
- Character editor bug fixed (#3200)
- Allow externally hosted Scratchpads to tweak their own configuration/user 1
- Allow filtering by any field in the VBO views (#3104)
- Fixed a bug with Slickgrid and views with arguments
- Only show NCBI data for valid terms (#2190)
- Display user references as full names (#2735)

2.1.6.1 (2013-08-05)

- Ensure editing of a site's URL aliases is enabled

2.1.6 (2013-07-31)

- Italicise subgeneric ranked taxa (#3138)
- Enabled the editing of a site's URL aliases
- Minor DwC-A additions for image metadata.
- Enable harvesting of site categories for the stats pages (#110)

2.1.5.2 (2013-07-21)

- Prevent body field from being deleted.

2.1.5.1 (2013-07-18)

- Ensure ITIS Term and Scratchpads Group updates run as expected

2.1.5 (2013-07-17)

- Various DwC-A bug fixes
- Tweaks to the presentation of Scratchpads statistics (#110)
- Prevent empty field_collection items from being created by Feeds imports
  (#3106)
- Added Vice Counties to the GM3 Regions (#2109)
- Character editor bug fixes (for those with the Character editor enabled)
  (#3129, #3125, #3127, #3099, #3113, #1210 #3108, #2262, #3097, #3098, #3095,
  #3096, #3112)
- Display the Entity/Bundle on search results pages (#3109)
- Added quotes to the Google Scholar API searches to get more specific results
  (#3124)
- Prevent deleting of stock Scratchpads fields (#3077)
- A link to open GeoCAT using the CSV view has been added to relevant taxon
  pages (#2431)
- Prevent each site from running Optimize on the Solr server
- Ensure hidden pages are correctly hidden
- Added SCRATCHPADS_VERSION constant for displaying of the Scratchpads version
  number
- Generate COinS on Biblio pages (#3082)
- Renamed the Taxonomy description field to Comments (#882)

2.1.4.1 (2013-07-04)

- Ensure one time logins work before a user has accepted the T&Cs

2.1.4 (2013-07-03)

- Updates redirect module to the latest "dev" version (Fixes a duplicate hashes
  issue)
- Display Scratchpads version on eMonocot sites (#2965)
- Tweak the taxonomy term description field (#882)
- Allow hiding of SPM fields (#911)
- Fixed issues with import/saving SPM (#2785, #2956)
- Updates to Scratchpads Statistics
- Hide the Character project (#3019)
- Prevent access to certain pages
- Check for missing files and delete records from the database (#3035)
- Created a specific CSV file for Ecological Niche modelling
- Further tweaks to the DwC-A
- Fix cloning of Biblio nodes (#3037)

2.1.3 (2013-06-19)

- Added a switch for displaying of thumbnails as scaled images (#1247)
- Enable the hiding of borders from tables (#2908)
- Tweaked the text displayed when "All rights reserved" is selected (#2972)
- Allow importing into certain fields in a field collection (#2375)
- Export field collection values (#3007)
- Ensure taxon description blocks on the front page are displayed (#3003)
- Enable the displaying of a Lucid key (#2952)
- Display TDWG regions on a taxon overview page (#2380)
- Expand the autocomplete box (#3014, #3011)
- Fix entityconnect buttons in Chrome (#3015)
- Add locations to the taxon CSV output for BioVeL/GeoCAT
- Allow filtering by a node reference field in Slickgrid (#3010)
- Improve formatting of vernacular names (#2898)
- Prevent users from tabifying blocks they shouldn't (#2975)
- Minor fixes to DwC-A
- Remove the Hashcash module (#2961)

2.1.2.2 (2013-06-07)

- Restored the code to scratchpads_audubon_core_update_7002()
- Removed the optional end dates from audubon core fields that are preventing
  the update from running.

2.1.2.1 (2013-06-07)

- Removed the code from scratchpads_audubon_core_update_7002()

2.1.2 (2013-06-05)

- Added additional update options for media files (#615)
- Ensure the default newsletter is available (#1123)
- Display links to other forums when viewing a forum/forum post (#1140)
- Link to taxon page description tabs from the front page, rather than specific
  nodes (#591)
- Ensure botanical classifications display synonyms correctly (#2893)
- Fix the filtering and sorting in the grid editor (#2889, #2203)
- Ensure the filter boxes are displayed in all tabs in the grid editor (#2849)
- Added and configured the Gravatar module on all sites (#464)
- Allow linking of taxon names in an import by TID or GUID (#2752)
- Filter EOL API images out of the media select box (#2815)
- Hide Editors from the literature pages (#2911)
- Allow "People" to have profile images (#2888, #2820)
- Type Arhive -> Archive (#2459)
- Display logos on training sites (#2874)
- Allow displaying of Biblio records for a "Person" (#1481)
- Allow users to edit the fields displayed in the lightbox (#2798)
- Link the points on a map to their specimens (#1421)
- Prevent tips from overlapping the date fields (#811)
- Ensure export of large quantities of data in feeds works as expected (#2914)
- Ensure all file fields use the Media select widget (#2143)
- Wipe unit indicator values if the corresponding unit name value has been wiped
  (#2928)
- Editing data in the location grid no longer removes GM3 data (#2048)
- Consistent spacing of the nomenclature block (#2936)
- Allow Slickgrid to work with page arguments (#2950, #2867)
- Allow deleting of large branches from the taxonomy editor (#1463)
- Ensure the validation is added to populated Excel templates (#2272)
- Fixed the DwC-A generation script
- Added a data integrity check for terms in a deleted classification
- Various Publication module fixes
- Ensure small images can be edited from the lightbox (#2701)
- Add descriptions to the Revision information checkboxes (#1102)
- Removed the content type facet from the literature pages (#2219)
- Upgraded Omega theme to 7.x-3.1

2.1.1 (2013-05-20)

- Ensure Primary menu links on Forum pages are displayed correctly (#2869)
- Disable changing the display of the Forum content type
- Change the URL of the training feedback form (#2873)
- Prevent an error when deleting files using Views Bulk Operations (#2587)
- Added a Blog sidebar block to allow filtering of blocks (#1303)
- Added a Forum sidebar block to allow easy navigation of fora (#1140)
- Upgraded the Apachesolr and Apachesolr Multisite Search modules
- Ensure that all indexable content is indexed
- Prevent an error on indexing sites without a biological classification
- Fixed bugs with Multisite Search the caused the whole index to be deleted
- Fixed a bug that prevented facets from displaying on the media gallery pages
- Prevent images associated with a gallery from being deleted if the gallery is
  deleted (#2694)
- Ensure that Scratchpads Messages are correctly and consistently formatted
- Ensure all vocabularies can be referenced in a term_reference field (#2856)
- Ensure logos are displayed on all new sites
- Ensure that the media browser displays images correctly
- BHL Widget now uses BHL APIv2 with a much improved overlay (#2833)
- Ensure that the Google Scholar and BHL widgets are displayed on the correct
  pages (#2833)
- Added a data integrity module to ensure basic data structures are not corrupt
- Allow users to see which version of Scratchpads they are using by hovering
  over the Scratchpads logo
- Performance improvement for the taxon page map blocks

2.1.0 (2013-05-08)

- Convert vernacular names to field_collections if the name is not blank
- Slickgrid now loads rows dynamically

- Moved the display of the taxonomic name field to the bottom of all content
- Ensure that there are no spaces after the hybrid indicator '×' (#2268)
- Removed old code
- Added the .zip extension to the allowed list (#999)
- Update the way views are counted by the stats module (#2521)
- Prevent the media browser from showing EOL API files (#2815)
- Ensure newly added terms are added to the terms reported by stats
- Ensure that page views are counted on cached pages
- Link to the "Scratchpads Policies" page (#2809)
- Only match lexicon terms on whole words (changed from left-match)
- No need to downgrade jQuery to 1.7 on views admin pages
- Updated plupload module to 7.x-1.1
- Updated Lexicon module to 7.x-1.10
- Updated Entity module to 7.x-1.1 (#2587)
- Updated Views module to 7.x-3.7
- Updated views_bulk_operations to 7.x-3.1

2.0.1.2 (2013-05-01+1)

- An intermediate update to help us upgrade to 2.1.0

2.0.1.1 (2013-05-01)

- Rerun the itis_term_7004 (now 7005) update to enable the languagefield and
  field_collection modules.

2.0.1 (2013-04-24)

- Upgraded Drupal to 7.22
- Prepared the sites to use Varnish
- Upgraded simplenews module to 7.x-1.0
- Ensure the file styles table can be populated (#1118)
- Fixed an issue with the Excel import that repeated some import rows
- Added images to the DwC-A export
- Ensure EOL API images are correctly displayed
- Enable statistics on all sites
- Enable users to reset the emails used by Femail
- Include a Last-Modified header for the DwC-A to aid caching
- Added Khalid Almaini's OpenID - the newest member of our team
- Added the cookieguard module, although not actually enabled
- Improved presentation handling of the user_reference fields
- Various Pensoft publication module fixes
- Removed the "beta" logo
- Open the help wiki in a new tab (#880).
- Prevent the WYSIWYG editor from expanding
