# Flutter_basics
Flutter Basics. CodeCademy

# A styled flutter Icon

import 'package:flutter/material.dart';

void main() {
  const myStyledIcon = Icon(Icons.breakfast_dining,
                        color: Colors.amber,
                        size: 100.0,);
  
  runApp(
    const MaterialApp(
      home: Scaffold(
        body: myStyledIcon
      )
    )
  );
}

# A styled Text widget

import 'package:flutter/material.dart';

void main() {
  
  const myStyledText = TextStyle(color: Colors.amber,
                                fontSize: 35);
  
    runApp(
    const MaterialApp(
      home: Scaffold(
        body: Text('My first styled text-widget! :)',
                  style: myStyledText)
      )
    )
  );
}

# Basic start structue in Flutter 

// An empty application
import 'package:flutter/material.dart';

void main() {

runApp(const MaterialApp(
  home: Scaffold()
    )
  );
  
}

# Review Lession 1. Flutter

Widgets
Widgets define our content, how it looks, and how it interacts with the user. They are the main way we create Flutter applications. We create widgets by calling their constructors with parameters defining their content.

Starting Our App
After we import the Flutter library, we define our app inside of main which calls runApp. Inside of that call we have the MaterialApp widget which provides important information about our app. Inside of MaterialApp we use the Scaffold widget, which provides our app with a structure.

Text
To create a Text widget, we simply call its constructor with the text we want to display. Other options can be provided as well.

Styling Text
To style Text, we pass a TextStyle object to the style attribute of a Text widget:
The TextStyle object allows us to specify things like fontSize and color.

Icons
Icons can be created by specifying an icon from Google’s list of icons. We can also specify a color and a size.





