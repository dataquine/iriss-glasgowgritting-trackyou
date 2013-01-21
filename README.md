Project: Glasgow Gritting, http://gccgritting.iriss.org.uk
===========================================================

Subproject: TrackYou
--------------------

This is one half of the system for the Glasgow Gritting project.
PHP server-side scripts do data processing of XML files generated by the 
Glasgow City Council's "TrackYou" GPS tracking system http://www.trackyou.co.uk

The scripts in this repository generate CSV, RSS and KML files from the TrackYou 
XML data for the open data download archives. These files are then aggregated 
by the Drupal content management system for display on the Glasgow Gritting
website. Code for the Drupal installation will be available in a separate 
repository.

For more details and links to the downloadable data see
http://gccgritting.iriss.org.uk/about/opendata

The source XML files are in a format that only Glasgow Council will have as 
TrackYou wrote a system specifically for the council to generate these files.
You can see an anonymised version of the kind of source data processed by this
system inside the sampledata directory.

Produced by IRISS, http://www.iriss.org.uk
for
Glasgow City Council, http://www.glasgow.gov.uk

This project was supported by Nesta - Make it Local Scotland 
http://www.nesta.org.uk/areas_of_work/public_services_lab/past_projects_public_services_lab/make_it_local_scotland/assets/features/make_it_local_scotland