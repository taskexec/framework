# task_execution

Add dependency in pom.xml
```
<dependency>
	<groupId>org.task.execution.framework</groupId>
	<artifactId>org.task.execution.framework</artifactId>
	<version>1.0.0</version>
</dependency>

public static void main(String[] args) {
        TaskScheduler ts = new TaskScheduler(ExampleOpt.class, args);
        ts.scheduleTask();
}

```

