
Sample that shows have Scala and GWT work together on Hello World application.

This project uses custom versions of GWT and Scala included in lib directory.

--
Build with:

  $ ant war

Then run the generated "./Hello.war" with jetty-maven-plugin:

  $ mvn jetty:deploy-war

Open browser at http://127.0.0.1:8080/.
