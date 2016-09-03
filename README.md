# SOATestingWithCitrus
A very simple, mavenised Oracle SOA 12c Composite with an associated, CI-ready citrus test harness.
*******Author: Jang Vijay  Singh

More in the associated blog post on http://weblog.singhpora.com

**To build+deploy+test, just run "mvn integration-test" from the application level
(provide serverUrl, user and password in the 
SOAComposite pom or from the environment e.g. -DserverUrl=http://soahost:soaport)

**To only run the integration tests, just run "mvn integration-test" from the SOACompositeTests level. 

**For more on Citrus, see:
http://www.citrusframework.org/

**To get hands-on, the maven archetype is a good starting point - allows you to create the shell
projects for SOAP and JMS testing:
http://www.citrusframework.org/reference/html/#setup-maven-archetype
