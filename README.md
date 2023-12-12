# Instafilter: Photo Editing App

## Overview
Instafilter is an iOS app that allows users to import photos from their library and apply various image effects using Apple's Core Image framework. The app seamlessly integrates with UIKit to offer a diverse range of filters, making photo editing both accessible and enjoyable.

## Key Features
- **Photo Import**: Users can select photos from their library for editing.
- **Filter Application**: Offers multiple filters like Sepia Tone, Gaussian Blur, Pixellate, and more.
- **Customizable Filter Parameters**: Users can adjust filter intensity, radius, and scale to customize the effects.
- **Image Saving**: Processed images can be saved back to the photo library.
- **UIKit Integration**: Utilizes `UIViewControllerRepresentable` to integrate UIKit's `PHPickerViewController` within SwiftUI.

## Technical Details
- **Core Image**: Leverages Core Image for real-time photo processing.
- **SwiftUI**: Built entirely with SwiftUI, ensuring a responsive and modern user interface.
- **Image Picker**: Integrates with the iOS photo library to allow users to pick images for editing.
- **Filter Adjustments**: Users can fine-tune filter settings using sliders that dynamically update the preview.

## Code Highlights
- **ContentView**: Manages the main interface, including filter selection and image display.
- **ImagePicker**: A wrapper around `PHPickerViewController` for selecting images from the photo library.
- **ImageSaver**: Handles saving edited images back to the user's photo library.

## Challenges and Skills
- Integrating Core Image with SwiftUI for a seamless image editing experience.
- Bridging SwiftUI with UIKit components for enhanced functionality.
- Managing state and reactivity in response to user input and filter changes.

---

*Instafilter was developed as part of the "100 Days of SwiftUI" course, focusing on practical application of Core Image and SwiftUI/UIKit integration.*

---
