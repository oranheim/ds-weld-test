# Build and test

mvn clean install -PWeld

or

cd helloworld
mvn clean test -PWeld

# Test failure

-------------------------------------------------------------------------------
Test set: com.acme.test.WeldTest                                 
-------------------------------------------------------------------------------
Tests run: 1, Failures: 0, Errors: 1, Skipped: 0, Time elapsed: 0 sec <<< FAILURE!
com.acme.test.WeldTest  Time elapsed: 0.002 sec  <<< ERROR!
org.jboss.weld.exceptions.DeploymentException: Exception List with 1 exceptions:
Exception 0 :
java.lang.IllegalStateException: Could not find beans for Type=class org.apache.deltaspike.core.impl.scope.window.WindowBeanHolder and qualifiers:[]

