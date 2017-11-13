Sample maven project containing a Java agent and examples of bytecode manipulation Javassist.


## Build

```
$ # From the root dir
$ mvn package
```

## Run

```
From the root dir

Without agent
$ java -jar prog-test\target\prog-test-0.1-SNAPSHOT.jar


With agent
$ java -javaagent:agent/target/agent-0.1-SNAPSHOT.jar -jar prog-test\target\prog-test-0.1-SNAPSHOT.jar


