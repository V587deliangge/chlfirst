###### java

1.  新建JAVA_HOME系统变量

   ![1556192037044](C:\Users\changhuangliang\AppData\Roaming\Typora\typora-user-images\1556192037044.png)



2.  在path变量中添加%JAVA_HOME%\bin;

3.  新建 CLASSPATH 变量

   .;%JAVA_HOME%\lib;%JAVA_HOME%\lib\tools.jar  

   **只有在 CLASSPATH 变量目录下的class文件才能运行**

4. 测试  `java  -version`

##### maven

1. 新建MAVEN_HOME系统变量

   ![1556192670212](C:\Users\changhuangliang\AppData\Roaming\Typora\typora-user-images\1556192670212.png)

2. 在path变量中添加%MAVEN_HOME%\bin;

3. 测试 `mvn -v`