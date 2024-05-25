# Interface CommandLineRunner (Class 20)

This is an interface provided by Spring Boot.
And basically it says when it detects this type of component on the class path or in this context,
I should say to pick it up and it's going to execute the run method.
So this is going to get picked up and run every time that Spring Boot starts up.
If it finds a class in the context that implements CommandLineRunner, it's going to execute that.