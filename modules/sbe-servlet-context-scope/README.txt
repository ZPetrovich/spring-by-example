This is a simple example making a custom scope in Spring for ServletContext scope.  
If no context is defined on ServletContextScope, the default ServletContext will be used.
Otherwise the specified context path will be used.  This is useful for servlet containers 
that have cross context support.

This project can be built using Maven (http://maven.apache.org).  It can also be imported into 
the Eclipse IDE, but the M2Eclipse plugin should be installed since it is used to resolve 
the classpath.


Release Notes
--------------
1.0.2 - Upgraded to Spring 3.2 & Servlet 3.0.

1.0.1 - Upgraded to Spring 3.0.

1.0 -	Initial release.