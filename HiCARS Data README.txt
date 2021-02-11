IceBridge HiCARS 1 L0 Raw Return Energy Amplitudes

DATA ORGANIZATION
The data files are available on HTTPS site:

https://daacdata.apps.nsidc.org/pub/DATASETS/ICEBRIDGE/IR1HI0_HICARS1raw_v01/

---------
NOTE on File Size Limit and Split Files

Many of the bxds binary data files exceed the NSIDC HTTPS server 2 GB size limit.
These data files have been split into 1 GB subfiles. The subfiles can be downloaded 
individually, and then re-assembed on your site after download. Each subfile is 
named with a two-number extension, such as .bxds.00, .bxds.01, etc. All of the 
subfiles must be downloaded to properly re-assemble the original data file. 

The original file larger than 2 GB, which cannot be downloaded, has no extension 
after .bxds.

Example original file: ICG1_JKB2d_GMHCOa_RADnh3.bxds
Subfile names:
ICG1_JKB2d_GMHCOa_RADnh3.bxds.00
ICG1_JKB2d_GMHCOa_RADnh3.bxds.01
ICG1_JKB2d_GMHCOa_RADnh3.bxds.02
ICG1_JKB2d_GMHCOa_RADnh3.bxds.03
ICG1_JKB2d_GMHCOa_RADnh3.bxds.04
ICG1_JKB2d_GMHCOa_RADnh3.bxds.05
ICG1_JKB2d_GMHCOa_RADnh3.bxds.06
ICG1_JKB2d_GMHCOa_RADnh3.bxds.07
After downloading all of the subfiles, the ICG1_JKB2d_GMHCOa_RADnh3.bxds file may 
be reassembled on a unix or linux system by concatenating the subfiles. This can 
be done with a wild card as:

cat ICG1_JKB2d_GMHCOa_RADnh3.bxds.* > ICG1_JKB2d_GMHCOa_RADnh3.bxds.WHOLE

The subfiles will reassemble in correct sequence by default using the wild card. 
Similar concatenation may be possible on Windows workstations as well. 
---------


The directory structure on the HTTPS site is organized by folders named 
according to campaign year, location, and source, such as:

/2009_AN_UTIG/

/2010_AN_UTIG/

/Documentation/


DOCUMENTATION
For complete documentation and more information about data access, please see:

http://nsidc.org/data/ir1hi0.html

We recommend that you read the complete documentation in detail before working with the data.


REGISTRATION
If you wish to be notified of updates or corrections to these data,
please register with NSIDC User Services by sending e-mail to:

    nsidc@nsidc.org

Identify yourself as a user of "IceBridge HiCARS 1 L0 Raw Return Energy Amplitudes (IR1HI0)". 
Include  your name, e-mail address, postal address, and telephone number.

Contact Information:
User Services
National Snow and Ice Data Center
CIRES, 449 UCB
University of Colorado
Boulder, CO USA 80309-0449
Phone: +1 303-492-6199
Fax: +1 303-492-2468
E-mail: nsidc@nsidc.org
