
Warning this code is in its original form over 2 years old, it should still work, tested on mac lion and snow leopard.

Setting up the server

portal is the media server UPNP to Bonjour bridge originally intended to be distributed with StreamX and StreamPad , build either of those to use with this.

Portal server must be run on your local network either private or addressable.

to run from eclipse unzip the file portal zip and import it, currently the format is for myEclipse, other versions will need to be imported manually

To run from the file system

cd into 

src/com/mcv/server/

In mediaClientStrings.properties

Enter your network ip, for the server the app is running on 

using java command line run the file mediaClient.class

It is also possible to run as an executable jar.

After making changes to the mediaclientStrings.properties

Compress the PortalServer folder and rename it to jar

click on the jar 

If you did everything correctly you should see a small window with the name of server and port.


On Windows you also need bonjour for windows .

http://www.apple.com/support/bonjour/

Make sure the dnssd lib is in win32/system directory.

\The mac has this library already.

cd to the portalserver1 folder 

there are two folders 

