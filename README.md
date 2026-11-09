# CustomSwipeAction iOS App

A simple and interactive iOS application built using **SwiftUI**, demonstrating custom swipe actions in a List.

## 📱 Screenshots

<img width="1179" height="2556" alt="Simulator Screenshot - iPhone 14 Pro - 2026-11-09 at 18 52 39" src="https://github.com/user-attachments/assets/a0789dd7-6fb9-434e-94da-897700a9af27" />

<img width="1179" height="2556" alt="Simulator Screenshot - iPhone 14 Pro - 2026-11-09 at 18 52 52" src="https://github.com/user-attachments/assets/0510492b-3665-4cd3-a9ce-ba84a41451c7" />

<img width="1179" height="2556" alt="Simulator Screenshot - iPhone 14 Pro - 2026-11-09 at 18 52 59" src="https://github.com/user-attachments/assets/b0378921-4700-4145-aa28-cb79ed8ab90e" />




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
