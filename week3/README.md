## May 2023 week 3

### Week[3][2] Externalized configuration
Today i learnt about Spring Cloud config server
and how this one helps cloud native applications to externalize configuration by reading it from a git repository, vault, file system among others.

As mentioned on cloud native spring book one also can externalize configuration through environment variables and JVM arguments.
Still when faced with packaging this applications as docker images, one would have to build this image again with the new environment variable value applied, and then deploy new instances as well, so that's when the config server really shines.

I still have the following questions:
- How about configmaps and secrets on kuberntes? Can they change dynamically? How do spring applications will know about it?

- How to refresh spring applications with actuator?
