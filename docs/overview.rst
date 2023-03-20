.. _over_view:

**********************
Overview
**********************

Current Version:  0.0.1a


The pensando-elk implementation the starting point for building and utilizing the Elasticstack for monitoring and analyzing
data, both about and traversing, the Pensando DSS(es) - DSC(s) coming soon - within your environment.  The purpose is to consolidate the
applications and tools used for said monitoring and analysis and deploy them in an automated fashion.


.. seealso:: For more information on each of the components in Pensando-ELK, visit the :ref:`components`

The recommended hardware needed to run a lab instance of pensando-elk:

    + 4 CPU
    + 16GB RAM - (up to 64GB supported)
    + 128GB HDD


To use pensando-elk, the host system needs docker and docker-compose installed before it can be instantiated.
The best way to install on Ubuntu is linked
  here `https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-22-04`_

  If you aren't running 22.04, select the appropriate OS version from the dropdown under the graphic right below the document title.  You can also use the same site (recommended) to install docker-compose.  The reason for installing both of these via the documented method is that they work.  The default repos in Ubuntu install older versions of docker that are *not* CE and work intermittently.

From there, you can :ref:`download-pensando-elk` and then :ref:`running-pensando-elk`
