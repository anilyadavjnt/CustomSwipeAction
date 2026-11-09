# CustomSwipeAction iOS App

A simple and interactive iOS application built using **SwiftUI**, demonstrating custom swipe actions in a List.

## 📱 Screenshots

<!-- Add your app screenshots here -->

| Home Screen | Swipe Action | Delete Action |
|---|---|---|
| Add Screenshot 1 | Add Screenshot 2 | Add Screenshot 3 |

## ✨ Features

- Display a list of user names.
- Custom swipe actions on list items.
- Delete action with destructive styling.
- Interactive swipe gestures.
- Clean and simple SwiftUI interface.

## 🛠 Technologies Used

- Swift
- SwiftUI
- Xcode
- iOS List
- SwipeActions
- SF Symbols

## 💻 Code Example

```swift
List {
    Text("Anil Yadav")
        .swipeActions {
            Button(role: .destructive) {
                print("Deleting")
            } label: {
                Label("Delete", systemImage: "minus.circle")
            }
        }
}
```

## 🚀 Getting Started

1. Clone this repository.
2. Open `CustomSwipeAction.xcodeproj` in Xcode.
3. Select an iOS Simulator.
4. Build and run the project.

## 👨‍💻 Developer

**Anil Kumar Yadav**

- GitHub: https://github.com/anilyadavjnt
- LinkedIn: https://www.linkedin.com/in/anilyadavjnt/

---

If you find this project useful, don't forget to ⭐ the repository!
