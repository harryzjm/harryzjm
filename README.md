<div align="center" style="display:flex;justify-content:space-around;align-items:center;">
  <img src="https://raw.githubusercontent.com/harryzjm/harryzjm/master/welcome.gif">
  <img height="200px" src="https://i.imgur.com/qRI7sXu.png">
  <img src="https://raw.githubusercontent.com/harryzjm/harryzjm.github.com/master/assets/photo/welcome.gif">
</div>

### Hi there, I'm Hares. 👋

```swift  
let introduce = [
    "📱" : "I now develop iOS applications, and used to be a Web developer.",
    "🤔" : "I'm focused on user interface design and user experience.",
    "🔨" : "I use Swift, Objective-C, Python, etc.",
    "🌱" : "I'm currently learning algorithm.",
    "💬" : "Send me email, if you want talk with me.",
    "🌟" : "I'm love functional reactive programming and all interesting techniques."
]

introduce
    .sorted(by: >)
    .map { $0 + ": " + $1 }
    .forEach { print($0) }
```  

```  
🤔: I'm focused on user interface design and user experience.
🔨: I use Swift, Objective-C, Python, etc.
📱: I now develop iOS applications, and used to be a Web developer.
💬: Send me email, if you want talk with me.
🌱: I'm currently learning algorithm.
🌟: I'm love functional reactive programming and all interesting techniques.
```  

