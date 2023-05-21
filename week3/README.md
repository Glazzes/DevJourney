## May 2023 week 3

### Week[3][2] Externalized configuration
Today i learnt about Spring Cloud config server
and how this one helps cloud native applications to externalize configuration by reading it from a git repository, vault, file system among others.

As mentioned on cloud native spring book one also can externalize configuration through environment variables and JVM arguments.
Still when faced with packaging this applications as docker images, one would have to build this image again with the new environment variable value applied, and then deploy new instances as well, so that's when the config server really shines.

I still have the following questions:
- How about configmaps and secrets on kuberntes? Can they change dynamically? How do spring applications will know about it?

- How to refresh spring applications with actuator?

### Week[3][5] GraalVM in the cloud
Today i learnt of GraalVM and it's role in cloud native applications, by reducing the start up time as well as the overall size and memory consumption.

I found pretty interesting that GraalVM can also convert `jar files` into `native images`

### Week[3][7] Portfolio v2
I just took a look at my portfolio and quickly said to myself "Hey! this is not what i am fully capable of", so i started to work on the new version, and it look way more profesional than v1, altough it's only half done.

Hope it's complete by the end of next week.