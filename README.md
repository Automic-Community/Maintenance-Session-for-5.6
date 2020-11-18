*Maintenance Session for 5.6*
=============


Dollar Universe Maintenance Session Unix and Windows rebuilt for $U 5.6
http://github.com/Automic-Community/Maintenance-Session-for-5.6

<!-- List of attached files -->
Contents of Solution Package:

						
								*Dollar_Universe-Maintenance.zip
								
						


Documenation and Instructions
---

<p>Dollar Universe Maintenance Session Unix and Windows rebuilt for $U 5.6<br /> <br /> The documentation is included in the zip file<br /> <br /> - Uprocs variables and launch date can be customized before installation in install.bat or install.ksh file.<br /> - Online Purge can be activated thanks to the installation.<br /> - Uprocs use "S_NODENAME" rather than "S_NOEUD" to solve issue with DU5.6.<br /> - More Binaries are available in the binaries directory (cut.exe...)<br /> - universe.log retention was corrected in windows. (Previously, the file was erased.)<br /> - Correction of the variable name UXARC_JOB_LOG<br /> - Documentation updated<br /> <br /> Please note that the maintenance session is delivered to North American customers through the Univkit, so these customers do not need to use this application.</p>
<p>&nbsp;</p>
<p><strong class="title">Implementation:</strong></p>
<p>The installation script is provided inside the binary archive.<br /> 1- Uncompress the archive Maintenance.zip<br /> 2- Load the Dollar Universe environment<br /> . &lt;/path/to/universe/COMPANY&gt;/mgr/uxsetenv<br /> <br /> 3a- Edit install.ksh and custom retentions values on Unix.<br /> 3b- Edit install.bat and custom retentions values on Windows. <br /> <br /> 4- If used, same for u_purge_param.ref in data repertory<br /> <br /> 5- Execute the installer<br /> ./Maintenance/install.ksh &lt;AREA&gt; &lt;local_mu&gt; &lt;optionnal : allow on ligne Purge y/n&gt;<br /> <br /> e.g. : <br /> ./Maintenance/install.ksh EXP frlpmps033<br /> <br /> e.g. with on ligne Purge : <br /> ./Maintenance/install.ksh EXP frlpmps033 y</p>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
