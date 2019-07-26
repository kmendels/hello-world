This TestFix applies to UrbanCode Deploy (UCD) [7.0.2.3.ifix01.1022337]

*****NOTE: 
It is mandatory to have UrbanCode Deploy (UCD) [7.0.2.3.ifix01.1022337] installed before applying this test fix.
This patch contains only js file change.
 

Details on the test fix:
-------------------------
This test fix addresses the following problem:
ucd-7.0.2.3.ifix01-PH13888-fixed-comp-env-prop-save-UI

This test fix includes the following patch files:
  zip file:
ucd-7.0.2.3.ifix01-PH13888-fixed-comp-env-prop-save-UI

How to apply the test fix:
---------------------------
1.Transfer the patch jar/zip file(s) to a temporary location on the file system.
2.Copy the patch zip file(s) into the <install_dir>/patches/web directory. If the "web" directory does not exist, create it.
3.Back up <install_dir>/opt/tomcat/webapps/ROOT/static/7.0.2.3.ifix01.1022337/ucdjs-pack.js and make note of the back up location.
4.Back up <install_dir>/opt/tomcat/webapps/ROOT/static/7.0.2.3.ifix01.1022337/js/deploy/widgets/environment/EnvironmentComponentProperty.js 
and make note of the back up location.
5.Extract the patch zip file(s) into the <install_dir> directory.
6. Clear the browser cache and then restart the server.

How to uninstall the test fix:
------------------------------
1.Replace the <install_dir>/opt/tomcat/webapps/ROOT/static/7.0.2.3.ifix01.1022337/ucdjs-pack.js with the backed up version.
2.Replace the <install_dir>/opt/tomcat/webapps/ROOT/static/7.0.2.3.ifix01.1022337/js/deploy/widgets/environment/EnvironmentComponentProperty.js with the backed up version.
