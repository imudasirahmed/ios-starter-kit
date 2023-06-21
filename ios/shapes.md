# Shapes
Shapes are like kdrawing lego compoents that can be applied to a View Component. Example: Image, Button etc
Shapes can also be applied as backgrounds to View Components

```swift
Circle()
  . fill(.purple)
  .foregroundColor(.yellow)
  .stroke()
  .stroke(.red)
  .stroke(.purple, lineWidth: 12)
  .frame(width: 200, height: 100)
  .cornerRadius(10)
```

