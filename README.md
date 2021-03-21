# FTB Presents Direwolf 20 1.16

Builds are automatically generated on push and on schedule to ensure image freshness.

![Build and Push Latest Versions](https://github.com/Xalaxis/FTB-Presents-Direwolf-20-1.16/workflows/Build%20and%20Push%20Latest%20Versions/badge.svg?branch=main)

A Docker container that runs the FTB Revelation modpack.

This container has -Dfml.queryResult=confirm set, which means that in the event of any mod removals between versions, the change will be silently accepted.

Images are available on DockerHub at wolfrazu/ftb-presents-direwolf20-116.  For specific versions, see the image label appropriate to the version you want. These are automatically generated with every new version.

## Example versions

* latest (Automatically updates to the latest version available) - Default
* 1.7.0

This one of my first public containers, so if you have any suggestions feel free to submit a pull request or issue :)