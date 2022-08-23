# TataAssignment
 1. Can we nest the Scaffold widget? Why or Why not?
    Ans : Yes it's possible to nest scaffold widget, but that's not the best approach if we need tabbed or nested navigations.
 
 2. What are the different ways we can create a custom widget ?
    Ans : We can create Custom widgets when we want custom look and feel or Ui, or when we want to re-use widgets we can create custom widgets. We can extend StatefulWidget or StatelessWidget and difining parameters.
    Example : We need a Custom Divider in our app, we could create a StatelessWidget which could take parameters like height and color of the divider, which could be used across our app

 3. How can I access platform(iOS or Android) specific code from Flutter?
    Ans : Plator specific code can be accessed via Platform Channels, there are two ways MethodChannel(communication using async method calls) and EventChannel(Communication using stream)

4. What is BuildContext? What is its importance?  
    Ans: BuildContext gives location of the widget in the WidgetTree, In flutter of() method uses the buildcontext to traverse through the WidgetTree to get the ancestor or InhertedWidget. Eg: Navigator.of(context), traverses from the widget above till it finds Navigator widget.

