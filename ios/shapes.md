# Shapes
Shapes are like kdrawing lego compoents that can be applied to a View Component. Example: Image, Button etc
Shapes can also be applied as backgrounds to View Components

```swift
Circle()
  .fill(Color("ColorScheme"))
  .fill(LinearGradient(colors:[.blue, .purple], startPoint: .topLeading, endPoint:.bottomTrailing))
  .foregroundColor(Color(.sRGB, red: 0.9, green: 0.1, blue: 0.8, opacity: 1))
  .stroke()
  .stroke(.red)
  .stroke(.purple, lineWidth: 12)
  .frame(width: 200, height: 100)
  .cornerRadius(10)
```

