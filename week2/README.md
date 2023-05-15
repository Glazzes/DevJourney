## May 2023, Week Two

### Week[2][1] Kubernetes vs Spring Cloud Eureka
Kubernetes is a very appealing technology to me, as stated by [Cloud Native Spring in Action](https://www.manning.com/books/cloud-native-spring-in-action)'s second chapter, it has built in service discovery as well as load balancing capabilities leavig Spring Cloud Eureka in a second place, SOOOOO when using OpenFeign interfaces, should i refer to a deployment or the service to talk to the application instances? That's something i must find out later on the book.

### Week[2][6] Frontend Testing
Today i decided to give a look to frontend testing, i'm used already to test my backend applications, but not so much on the frontend, i just of testing library and jest today, as well as mocking with `jest.fn`

### Week[2][7] Kubernetes and gradle pre compiled plugins
Created my first deployment and service, when creating a service by default this one will not expose your app to the world, therefore it must be forwarded by using `kubectl port-forward`, haven't reach out yet to the section when we talk of ingress.

Gradle precompiled plugins can not have defined plugins within it's `[plugin-name].gradle`'s plugin definition, forcing the user to declare this plugins as implementation dependecies within pre compiled `build.gradle`'s dependencies closure, they require the full dependency name match the group, aritifact and version, luckily there's an easier way to tackle this program, they can be declared by following the next patern: "`[plugin-name]`:`[plugin.name].gradle.plugin`:`version`", for instance: `io.springframework.boot:io.springframework.boo.gradle.plugin:3.0.6`