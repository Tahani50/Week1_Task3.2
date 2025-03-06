# SwiftUI User Profile App

## Description
This SwiftUI application allows users to enter and update their name, while also providing a toggle to switch between light and dark mode. It utilizes the `@StateObject` property wrapper to manage state using an `ObservableObject` ViewModel (`UserProfileModel`).

## Features
- **User Name Management:**
  - Displays a default name (`Tahani Ayman`).
  - Allows users to update their name using a `TextField` and `Button`.
- **Dark Mode Toggle:**
  - Users can switch between light and dark modes using a `Toggle`.
  - The background color and text color adjust accordingly.
- **State Management:**
  - `@Published` properties are used in `UserProfileModel` to manage name updates.
  - `@StateObject` ensures the ViewModel persists across view updates.
  - `@Binding` is used to pass the dark mode state to a separate `ColorToggle` view.

## How It Works
1. The app starts by displaying the default name "Tahani Ayman".
2. The user can enter a new name in the `TextField`.
3. Pressing the "Change" button updates the displayed name.
4. A `Toggle` switch allows the user to switch between light and dark themes.
5. The UI dynamically updates based on the user's interactions.

## Technologies Used
- **SwiftUI**
- **State Management with @StateObject, @Published, and @Binding**

## Usage
1. Open the project in Xcode.
2. Run the app on an iOS simulator or device.
3. Enter a name in the `TextField` and press "Change" to update the name.
4. Toggle "Dark Mode" to switch themes.
