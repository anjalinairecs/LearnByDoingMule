# LearnByDoing - Mule

This is a humble effort from my side to help anyone trying out Mule for the first time :)

## Setup

The first step is to install AnypointStudio. This is an eclipse based environment that simplifies the process of creating Mule APIs. This IDE comes packed with the mule server as well, so there is no need to download it separately.

1. Check the prerequisites [here|https://docs.mulesoft.com/mule-runtime/4.2/hardware-and-software-requirements]
2. Download the studio from [here|https://www.mulesoft.com/platform/studio?utm_source=google&utm_medium=cpc&utm_campaign=g-brands-emea-search-anypoint-studio&utm_term=%2Bdownload%20%2Banypointstudio&utm_content=1t1-g-b-c&gclid=Cj0KCQjw1MXpBRDjARIsAHtdN-0PgX3W2WAMONT8rR1lMquI0nKeM3VQ5Sbgr7i1A-1VDMCWsJf0wjsaAoBhEALw_wcB]. You may need to create a new user account.	
2. Installation is pretty straightforward, and I know you are smart enough to figure it out :D

### Troubleshooting

#### Jdk version > 1.8 ? "oh no, read on.." : "continue to next section --Reading material--"
So, currently, Mule 4 is the latest version, and it requires JDK 1.8. If you have a jdk version > 1.8 installed in your machine, and that is what JAVA_HOME points to, you need to make some changes :(

1. Install Jdk 1.8. 
2. Open the file <AnytimeStudio-installation-folder>/Contents/Info.plist aith an editor of your choice. Check for the key 'Eclipse'. Add the path to JDK 1.8 as mentioned in the comments.

## Reading material

Mulesoft has some excellent reading material [here|https://docs.mulesoft.com/general/]. Each and every concept is explained with examples, so it would be a good idea to keep it opened in a browser, and refer to it while you go through the examples.

## Examples

Disclaimer : This is a work in progress, so it may have some errors/issues. Pull requests are the way to go :)

### Example 1 : Hello World

A simple Rest API that prints hello world.

