# flutter_calendar

A calendar widget for Flutter Apps.



## Usage

Add to your pubspec dependencies:
```dart
    flutter_calendar: ^1.0.0
```

Render the map with one of three options:

#### 1. Default, Material Design

```dart
new Calendar()
```



***

#### 2. An Expandable Map 

```dart
new Calendar(
  isExpandable: true;
)
```


***

#### 3. Customize It (Standard or Expandable)

```dart
new Calendar(
  // A builder function that renders each calendar tile how you'd like.
  dayBuilder: (BuildContext context, DateTime day) {
      return new Text("!");
  },
)
```

![day builder](http://res.cloudinary.com/ericwindmill/image/upload/c_scale,h_500,w_231/v1518649516/Simulator_Screen_Shot_-_iPhone_X_-_2018-02-14_at_15.04.04_jtranm.png)

***

### API
```dart
// Three optional params:
final VoidCallback onDateSelected;
final bool isExpandable;
final Widget dayBuilder;
```
  
