Eric Jaroszewski:

1.  Because in log.properties, we set the level of the FileHandler to ALL, whereas the ConsoleHandler's level is only INFO.
1.  It came from the Tester class when checking the enabled() function to see if the test was enabled.
1.  It passes the test if the specified exception gets thrown by the specified code segment, and fails the test if the specified exception does not get thrown.
1.  See TimerException and there are 3 questions
    1.  serialVersionUID is a version number used during deserialization to verify that the sender and receiver of a serialized object have loaded classes for that object that are compatible with respect to serialization. We need it because the default serialVersionUID provided by Java is not guaranteed to work when a private field is added to a class.
    2.  The Exception class does not define any constructors on its own, so we must override them.
    3.  The Exception class inherits all other methods from the Throwable class, so we have those readily available.	
1.  It executes only once when the Timer is created, and initializes the handlers for the logger object via the log.properties file.
1.  .md is short for MarkDown syntax, which is what BitBucket Server uses for formatting text.
1.  The test fails because a NullPointerException is thrown when timeNow is referenced from the finally{} block.
1.  NullPointerException is thrown after the TimerException, and as such gets caught by the Test first.
1.  Make a printScreen of your eclipse JUnit5 plugin run (JUnit window at the bottom panel) 
1.  Make a printScreen of your eclipse Maven test run, with console
1.  TimerException is a Checked Exception and NullPointerException is an Unchecked Exception.
1.  Push the updated/fixed source code to your own repository.