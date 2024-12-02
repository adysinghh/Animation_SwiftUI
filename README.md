# SwiftUI Animations - Landmarks Tutorial  
This repository focuses on the **"Drawing and Animation"** section from Apple's SwiftUI tutorial. It demonstrates how to add animations to a SwiftUI app for creating dynamic, responsive user interfaces.

## Overview  
SwiftUI simplifies adding animations to your app by managing complex, overlapping, and interruptible animations. This tutorial implements animations for tracking and visualizing user hikes in the **Landmarks** app.

### Features  
- Animate individual view transitions and property changes.  
- Explore advanced animations like springs, delays, and ripple effects.  
- Learn to create custom transitions for inserting and removing views.  
- Combine animations for more complex effects.  

## Tutorial Sections  

### 1. **Add Hiking Data to the App**  
Prepare the app to display hiking data by:  
- Importing JSON data.  
- Creating and using the `Hike` model.  
- Adding static views to visualize hiking data.  

### 2. **Add Animations to Individual Views**  
Enhance UI components by animating their properties, such as:  
- Rotation.  
- Scaling.  
- Applying different animation types (e.g., `spring()`, `easeInOut`).  

### 3. **Animate State Changes**  
Use `withAnimation` to apply animations to transitions triggered by state changes.  

### 4. **Customize View Transitions**  
Develop custom transitions with the `transition(_:)` and `AnyTransition` modifiers:  
- Create asymmetric transitions.  
- Animate views to slide, fade, or scale.  

### 5. **Compose Complex Animations**  
Combine animations to create ripple effects when visualizing graphs:  
- Use spring animations with custom damping values.  
- Add delays to animate graph capsules dynamically.  

## Prerequisites  
- **Xcode 15** or later.  
- **Swift 5.8** or later.  
- Familiarity with SwiftUI basics.  

## Getting Started  

1. **Clone the repository:**  
   ```bash  
   git clone https://github.com/adysinghh/Animation_SwiftUI.git
   cd SwiftUI_Animations  
   ```  
2. **Open the project in Xcode:**  
   Double-click `SwiftUI_Animations.xcodeproj`.  

3. **Run the app:**  
   - Choose a simulator or a connected device.  
   - Press **Run** or `Cmd + R`.  

4. **Explore animations:**  
   Experiment with animation modifiers and transitions in the provided views.  

## Preview  

### Hiking Data Visualization  
Animated transitions make the graph dynamic, adding visual interest and clarity.  

### Button Animations  
Interactive buttons with rotation, scaling, and custom transition effects.  

### Graph Ripple Effect  
Smooth, delayed transitions for graph capsules create a ripple effect when switching datasets.  

## Contributing  
Feel free to contribute by submitting pull requests for bug fixes or enhancements.  

## Resources  
- [SwiftUI Essentials - Apple Tutorial](https://developer.apple.com/tutorials/swiftui/animating-views-and-transitions)  
- [SwiftUI Documentation](https://developer.apple.com/documentation/swiftui/)  
