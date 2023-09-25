## What is variable scope?
Variable scope determmines the ability for access to a declared variable. Variables declared on the global level or 'class variables' can be accessed by all methods. Whereas variables declared within a method can only be accessed within that method i.e. locally. 

public class MainClass {

  int globalVariable = 10; //Global / class variable / field - all methods can access this

  private void methodOne () {
    int methodOneVariable = 20; // local variable - Only methodOne can access
    globalVariable - accessible from the global scope
  }

  private void methodTwo () {
    int methodTwoVariable = 20; // local variable - only methodTwo can access
  }

}
