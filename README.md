Android Flavor and Build Type Demo
Overview
This repository serves as a demonstration of how to use Android product flavors and build types in a Gradle-based Android project. The project showcases a simple Android app with two variants: a "Free" version and a "Paid" version. The key difference between the two versions is the appearance of a TextView with a unique color scheme for each.

Project Structure
app module: Contains the main Android application code.
src/main: Common code shared by both flavors.
src/free: Free version-specific code and resources.
src/paid: Paid version-specific code and resources.
Features
Product Flavors: The project defines two product flavors, "free" and "paid," under the "default" flavor dimension. This allows for customization of certain attributes like application ID and version name.

Build Types: The project includes default build types like "debug" and "release." Additionally, the "paid" flavor introduces a custom build type, "premium," demonstrating how to create variant-specific build configurations.

UI Customization: The TextView in the layout has different color schemes for the "free" and "paid" versions, providing a visual representation of how product flavors can be used to create distinct app variants.

Open the project in Android Studio.

Explore the different flavor and build type configurations in the Gradle files.

Run the app in different build variants to observe the visual differences.

Learnings
By exploring this project, you can learn:

How to set up product flavors and flavor dimensions in Gradle.
Customizing build types for different application variants.
Implementing variant-specific resources and code.
Using flavors to create distinct app versions with shared and unique characteristics.
