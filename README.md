Vaadin 7 add-on **ResetButtonForTextField** version 1.0. Also an example project for my blog post.

Usage: add the JAR to your project, compile widgetset and extend any TextField:

    TextField tf = new TextField();
    new ResetButtonForTextField().extend(tf);