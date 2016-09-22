LLSpinner
===========

Simple and easy to use full screen activity indicator written in Swift

![llspinner](https://cloud.githubusercontent.com/assets/7674479/18743621/3a5047f4-80fd-11e6-9701-e389caacab05.gif)

Easy to use
----

### Get Started

```swift
// Show spinner
LLSpinner.spin()

// Hide spinner
LLSpinner.stop()
```

### Controls

#### Custom Appearance

```swift
// You can modify the background color and the activity indicator style
// To set the default background color
LLSpinner.backgroundColor = UIColor(white: 0, alpha: 0.6)

// and the default activity indicator style
LLSpinner.style = .whiteLarge

// Or
LLSpinner.spin(style: .whiteLarge, backgroundColor: UIColor(white: 0, alpha: 0.6))
```

#### Tap

```swift
// Add a handler that will trigger when the spinner is tapped
LLSpinner.spin() {
   LLSpinner.stop()
}
```

