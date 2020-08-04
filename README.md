# SimpleTwitterStreamImpl
A Twitter Stream implementation built on Java using Twitter4J library.

Twitter4J - [referenece](http://twitter4j.org/en/)

## Requirements: 

1) Oracle Java / OpenJDK - 8+
2) Apache Maven
3) A Twitter Developer application with valid client and access keys generated.

## Usage: 

1) Download source to a folder
2) Build the project using "mvn clean install" command
3) You will find two files in the target folder : twitter-stream-impl-1.0.0-SNAPSHOT.jar, twitter-stream-impl-1.0.0-SNAPSHOT-jar-with-dependencies.jar
  **twitter-stream-impl-1.0.0-SNAPSHOT-jar-with-dependencies.jar is a standalone jar with all dependencies included.**
4) set the following variables in the environment(in Windows *set* in **CMD** and in Linux *export* in  **TERMINAL**):
  twitter4j.oauth.consumerKey = // your client key
  twitter4j.oauth.consumerSecret = // your client secret
  twitter4j.oauth.accessToken = // your access token
  twitter4j.oauth.accessTokenSecret = // your access token secret
  ** above are the keys obtained from the Twitter developer application**
5) Now run the java -jar /path-to-jar/twitter-stream-impl-1.0.0-SNAPSHOT-jar-with-dependencies.jar
