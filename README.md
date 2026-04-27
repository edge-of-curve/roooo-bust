# roooo-bust
a custom server software 
A independeted project to bring avx / neon mainstream to server while
maintaining the vanilla nature  

how TO USE ?? 
u get a zip file from relaese 
u need to get official minecraft server.jar (version depending on the on release u downloaded) 
open the official server.jar via 7-zip
open META-INF
open versions 
and open stuff until u found another jar file inside 
open the jar 
now select the the files from the zip file in the release (actual modifictaions are inside) 
drop them inside the jar u opened and last step 
open the META-INF folder again inside the second jar and delete any other files except LICENSE and MANIFEST.MF 
*optional thing 
still inside the 2nd jar open net folder inside minecraft folder delete gizmos folders as found in testing it
is useless ? yeah u can delete it if u want ..
and now after saving all these changes 
run this command in command prompt:- 
*  java -Xmx2G -Xms2G --add-modules jdk.incubator.vector -jar [YOURSERVER_JAR_NAME].jar nogui  *
and boom it is good to go after accepting th eula . 
additionally u can see some options in Switch.txt after the server is opened



