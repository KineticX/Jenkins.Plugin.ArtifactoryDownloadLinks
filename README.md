Jenkins.Plugin.ArtifactoryLinks
===============================

Description: 

Artifactory Download Links creates links to Artifactory published modules/artifacts directly in the Jenkins build info page. This allows Jenkins to display the artifacts deployed for a given build without the need to host them directly in Jenkins. 

More Information:

It achieves this by parsing the build output console log and looking for "Deploying artifact: " keywords and parsing the link to the deployed module / artifact in artifactory.
