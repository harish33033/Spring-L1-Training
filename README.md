# Spring-L1-Training



web.xml
<
servlet
>
<
servlet-name
>
telusko
</
servlet-name
>
<
servlet-class
>
org.springframework.web.servlet.DispatcherServlet
</
servlet-class
>
</
servlet
>
<
servlet-mapping
>
<
servlet-name
>
telusko
</
servlet-name
>
<
url-pattern
>
*.
htm
</
url-pattern
>
</
servlet-mapping
>
Maven dependency (pom.xml)
<
dependency
>
<
groupId
>
junit
</
groupId
>
<
artifactId
>
junit
</
artifactId
>
<
version
>
3.8.1
</
version
>
<
scope
>
test
</
scope
>
</
dependency
>
<
dependency
>
<
groupId
>
org.springframework
</
groupId
>
<
artifactId
>
spring-context
</
artifactId
>
<
version
>
4.1.8.RELEASE
</
version
>
</
dependency
>
<
dependency
>
<
groupId
>
org.springframework
</
groupId
>
<
artifactId
>
spring-
webmvc
</
artifactId
>
<
version
>
4.1.8.RELEASE
</
version
>
</
dependency
>
<
dependency
>
<
groupId
>
mysql
</
groupId
>
<
artifactId
>
mysql
-connector-java
</
artifactId
>
<
version
>
5.1.36
</
version
>
</
dependency
>
<
dependency
>
<
groupId
>
javax.servlet
</
groupId
>
<
artifactId
>
jstl
</
artifactId
>
<
version
>
1.2
</
version
>
</
dependency
>
telusko-servlet.xml
<
beans
xmlns
=
"http://www.springframework.org/schema/beans"
xmlns:ctx
=
"http://www.springframework.org/schema/context"
xmlns:xsi
=
"http://www.w3.org/2001/XMLSchema-instance"
xmlns:mvc
=
"http://www.springframework.org/schema/mvc"
xsi:schemaLocation
=
"http://www.springframework.org/schema/beans
http://www.springframework.org/schema/beans/spring-beans-2.5.xsd
http://www.springframework.org/schema/mvc
http://www.springframework.org/schema/mvc/spring-mvc-3.0.xsd
