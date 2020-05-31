---
layout: post
title:  "View modifiers order in SwiftUI"
date:   2020-05-31 16:00:00 -0400
categories: swiftui viewmodifiers
---

The order view modifiers are applied to a view in SwiftUI is super important. It may seem like a trivial thing and may be it is
and would eventually become skin memory however because the framework is new, it seems a big deal to me to get it right.

- Here i am applying background to the Text view and padding after it(i have bordered to them so its easy to view and understand)
```
Text("Tap me")
   .background(Color(.tertiarySystemFill))
   .border(Color.green)
   .padding()
   .border(Color.red)
   .cornerRadius(5)
```
![](images/swiftui-1-bg-padding.png)

- Here i am applying padding first(it adds padding to the Text view) and then background. Again, border for debugging.
```
 Text("Tap me")
    .padding()
    .border(Color.red)
    .background(Color(.tertiarySystemFill))
    .border(Color.green)
    .cornerRadius(5)
```
![](images/swiftui-1-padding-bg.png)

Salaam.
