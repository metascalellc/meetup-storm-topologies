Example Storm Topologies using Meetup's RSVP stream
============

This project uses:

1. Spout that reads Meetup's RSVP Stream
2. Bolt that writes to local Redis 

*This project uses Redis*
Download Redis from here: http://redis.io/download

If you want to eliminate Redis communication, remove/comment the lines in the RedisBolt that involve 'jedis'.

This is a maven-based project. You will need maven.

Quickest way to run the project:

1. mvn package
2. cd into the target directory and run 'java -jar storm-meetup-0.0.1-SNAPSHOT-jar-with-dependencies.jar'



