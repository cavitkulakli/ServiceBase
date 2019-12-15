# ServiceLayer

That is the basic service layer for learning about gradle project's how is works.

### Prerequisites


* [JDK 1.8 or later](https://www.oracle.com/technetwork/java/javase/downloads/index.html)
* [Gradle 4+](https://gradle.org/install/)
* [IntelliJ IDEA](https://www.jetbrains.com/idea/download/) or your favorite idea

### Installing

That is the basic application for gradle project setup only run code and call service here.

You’ll build a service that will accept HTTP GET requests at:
```
localhost:8080/first-api
```

response:
```
{"id":1,"content":"Hello, World!"}
```

You can customize the content with an optional name parameter in the query string:

```
localhost:8080/first-api?name=Cavit
```
The name parameter value overrides the default value of "World" and is reflected in the response:
```
{"id":1,"content":"Hello, Cavit!"}
```


## Authors

* **Cavit Kulakli** - *Personal development* - [CavitKulakli](https://github.com/cavitkulakli)
