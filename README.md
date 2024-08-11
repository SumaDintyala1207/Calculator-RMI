# Calculator-RMI
The Calculator-RMI project shows how Remote Method Invocation (RMI) works in Java. This example shows a simple Java RMI system - A Calculator. <br/>
This project has four files: <br/>
- Calculator
- CalculatorImplementation
- CalculatorServer
- CalculatorClient
- CalculatorClient1
- CalculatorClient2
- CalculatorClient3
<br/>
**Calculator** <br/>
- In this interface, an interface named 'Remote' is imported from the 'java.rmi' package. 'Remote' interface is necessary for any object in an RMI project to be used remotely. <br/>
- The class 'RemoteException' is imported from the 'java.rmi' package which is a checked exception that can occur during remote method calls to various network-related issues. <br/>
- 'extends' indicates that the Calculator interface is meant for remote access. <br/>
- pushValue(int val): Pushes a given integer value onto a stack managed by the server. <br/>
- pushOperation(String operator): Pushes the operations - min, max, lcm, gcd - onto the stack to perform specified operations. <br/>
- int pop(): Removes and returns the top element from the stack.<br/>
- boolean isEmpty(): Returns 'True' if the stack is empty. <br/>
- int delayPop(int millis): Waits for speciefied milliseconds before performing the 'pop' operation. <br/>
<br/>
In summary, Calculator defines the remote operations that can be performed.
<br/>
**CalculatorImplementation** <br/>

