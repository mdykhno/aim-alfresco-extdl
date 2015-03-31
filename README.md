Datalist Extensions for Alfresco Share (for Alfresco 5.0.x)
===========================================================

&lt;Ixxus&gt;

NB this branch has been modified by Ixxus for use at the HMH CMS project.

Alfresco version:
Alfresco Enterprise 5.0.0.5

Project information:
https://ixxuswiki.atlassian.net/wiki/display/HMH

Related task:
https://ixxuswiki.atlassian.net/wiki/display/HMH/HMHMVP-132+-+prevent+users+from+changing+HMSI+Standards+data

&lt;/Ixxus&gt;


This project is the Alfresco 4.2.x port of fme's datalist extensions.  I switched to github and maven because I personally don't like svn and ant. For now, the documentation remains at [google](http://code.google.com/p/fme-alfresco-extensions/wiki/DatalistExtension).

Alfresco 5 is now the primary target. The master branch may still work with 4.2.x.

===========================================================


Installation
============

* Run `mvn package`
* Put `./fme-alfresco-extdl-share/target/fme-alfresco-extdl-share-1.3.jar` in `tomcat/shared/lib` or `tomcat/webapps/share/WEB-INF/lib`
* Put `./fme-alfresco-extdl-repo/target/fme-alfresco-extdl-repo-1.3.jar` in `tomcat/webapps/alfresco/WEB-INF/lib`

Customization Example
=====================
See repo custom context for an approach: https://github.com/tass01024/fme-alfresco-extdl/blob/master/fme-alfresco-extdl-repo/example/my-custom-datalists-context.xml

Thanks Jan for supporting me !
