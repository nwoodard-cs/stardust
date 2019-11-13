# Project Stardust
&nbsp;
## Getting Started

&nbsp;
### Build the Project .jar with Dependencies
Build with Maven
```
mvn assembly:assembly -DdescriptorId=jar-with-dependencies
```
Run the project with Java
```
java -cp target/Stardust-[version]-jar-with-dependencies.jar
```
&nbsp;
### Build the Project .jar without Dependencies

Build with Maven
```
mvn verify
```
Run the project with Java

```
java -cp target/Stardust-[version].jar Stardust
```
