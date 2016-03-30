# iOS Bubble Transition
Transition between controllers coding in Swift. The transition starts at... better take a look below.

![Bubble Transition](https://github.com/fitomad/iOS-Bubble-Transition/blob/master/Bubble.gif?raw=true)

## Code
You only need two files:

- `BubbleTransition.swift`
- `TransitionMode.swift`

## Example
Here It is `BubbleTransition` in action

```swift
let bubble: BubbleTransition = BubbleTransition()

bubble.startingPoint = someButtonYouTap.center
bubble.transitionMode = TransitionMode.Present
// The background color for bubble.
// If not define the transition takes the 
// presented controller background color
bubble.bubbleColor = UIColor.blueColor()
```

## Contact
Questions? You can find me on **twitter** [@fitomad](https://twitter.com/fitomad)
