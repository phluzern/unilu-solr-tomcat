unilu-solr-tomcat
=================

Solr/Tomcat installation and configuration for TYPO3 Solr 3.0 with Solr 4.8

Since there are no official Ubuntu packages for Solr 4.8 yet, our hosting provider cannot provide us with a Solr service.

Thanks to sufficient rights Solr/Tomcat can allowed on own responsibility with the install script from the TYPO3 Solr extension.

This install script requires root permissions, therefore it was adapted not to require root permissions and to install Solr inside

    /home/www-data/solr-tomcat
    
Besides from that, some paths had to be adapted to point to this directory. This is the reason why the whole installation is versioned on GitHub.
