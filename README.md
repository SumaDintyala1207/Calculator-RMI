# Calculator-RMI
The Calculator-RMI project shows how Remote Method Invocation (RMI) works in Java. This example shows a simple Java RMI system - A Calculator. <br/>
This project has four files: <br/>
- Calculator
- CalculatorImplementation
- CalculatorServer
- CalculatorClients
<br/>
##Calculator##
In this interface, an interface named 'Remote' is imported from the 'java.rmi' package. 'Remote' interface is necessary for any object in an RMI project to be used remotely. <br/>
The class 'RemoteException' is importd from the java.rmi package which is a checked exception that can occur during remote method calls to various network-related issues.
