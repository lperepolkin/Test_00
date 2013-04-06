Careerbeacon
============

To set up you will need two configuration files.  You can find linux/windows examples in **src/config/dev_examples**. 

* The first is **mb.config.html** which must reside somewhere within the include_path defined in your php.ini.
* The second is **mybeacon/jobgo/application/config/config.php**.  The location of this file matters due to hard coded absolute paths expecting the file in a specific location.  To use either version, copy the desired mybeacon folder to src/www.


----

March 5, 2013:

This repo has the following content:

src/www/ - this contains all of the prod code from the snapshots provided on Mar 5/2013.  Backup files (anything ending with .bak, ~, *.tgz, or YYYYMMDD) were first removed. Other un-needed files - MacOS files (.DS_Store, __MACOSX) and Thumbs.db -  were also removed.


_bin - from 20130305._bin.tar, with *.html.1, *.html.2 and *.html.3 files removed

_fonts - from 20130305._fonts.tar, with ttf-bitstream-vera-1.10.tar.bz2 removed

_inc - from 20130305._inc.tar, only the current mb.config.html has been encrypted and put into src/config/

maintenance - from 20130305.maintenance.tar

_template - from 20130305._template.tar

widget - from 20130305.widget.tar (Note: the assumption is that the weblocal directories on both apache1 and apache2 are identical) with the widget_jan23_2013 and SQL directories removed


widget-v1 - from 20130305.widget-v1.tar

mybeacon - from 20130305.mybeacon.tar, with the files previously identified as dynamic removed (mostly mybeacon/admin/RSS*, but also mybeacon/admin/export_vcf.rtf,mybeacon/admin/inc/mbcity.js, and mybeacon/nfld/rss_last_3_days.xml)


src/config/ 

  svn_config/ - this has the contents of the svn_config directory as migrated from svn
  _inc/ - this has an encrypted copy of the production mb.config.html, as well as a default version of this file




