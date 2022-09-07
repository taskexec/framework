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
![image](https://user-images.githubusercontent.com/113044143/188921752-ade6dd79-ad0d-42b7-bb8e-d51716f4b6e1.png)


![image](https://user-images.githubusercontent.com/113044143/188921817-1bf5979e-c987-4f32-8038-7a80128ed729.png)
