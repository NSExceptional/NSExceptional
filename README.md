## Hi, I'm Tanner 🐈‍⬛

_Full time iOS dev_  
_Part time hacker / tinker_  

```logos
%hook Engineer // Ask me what language this is!
- (id)init {
    self = %orig;
    self.name = @"Tanner";

    // I dabble in a lot more than this, but these are my big 3 😊
    self.languages = @[@"Swift", @"Objective-C", @"TypeScript"];

    // Writing jailbreak tweaks is what got me into making iOS apps;
    // these are all skills I picked up along the way 🔧
    self.skills = @[@"Debugging", @"Performance Profiling", @"Reverse Engineering"];

    // Again, I dabble in more than these :)
    self.frameworks = @[@"UIKit", @"SwiftUI", @"Node", @"React"];

    return self;
}
%end
```

<details>
    <summary>
        <h3>My Favorite Projects</h3>
    </summary>

<table>
    
<tr>
<td><strong>Jsum</strong></td>
<td colspan=2>

A Swift Codable replacement that uses reflection to create types and map values.<br/>
No Codable, no Macros—just runtime magic 🪄✨
<br/>
<br/>

```swift
let person: (name: String, age: Int) = try Jsum.decode(
    from: ['name': 'Bob', 'age': 25]
)
```

</td>
</tr>

<tr>
</tr>

<tr>
    <td><strong>FLEX</strong></td>
    <td>A popular in-app debugging tool, capable of almost anything you can think of, from exploring the view hierarchy to calling methods in real time.</td>
    <td><img src=https://github.com/user-attachments/assets/a9786af4-9032-47cb-94fe-ab5a75d77b07 height=100px></td>
</tr>

<tr>
</tr>

<tr>
    <td><strong>Pastie</strong></td>
    <td>A clipboard manager for iOS that started as a jailbreak tweak, which I later turned into a full app. The tweak can be invoked from the keyboard in any app.</td>
    <td><img src=https://github.com/user-attachments/assets/9d46391b-4b3c-4847-bbab-a144987a8d92 height=100px></td>
</tr>

<tr>
</tr>

<tr>
    <td><strong>Receiptie</strong></td>
    <td>A receipt tracking app that uses OCR and AI to scan and organize your paper or email receipts for safekeeping. (Closed source)</td>
    <td><img src=https://github.com/user-attachments/assets/7e2e53a4-5b0d-4806-8509-26e6b644dc27 height=100px></td>
</tr>
</table>

</details>
