# Container Controllers

## adopt a controller

```swift
// The idea is this:
// parentViewController.view.addSubview(ChildViewController.view)
// parantViewController.addChild(childViewController)
// childViewController.didMove(toParent: parentViewController)

// If we are in a View Controller context, we would say:
view.addSubview(childController.view)
addChild(childController)
childController.didMove(toParent: self)
```

