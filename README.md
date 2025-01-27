# Parks - Explore National Parks Across the United States

**Parks** is a mobile app designed to help users discover national parks across the United States. With a clean and intuitive interface, users can view a list of parks, tap to get detailed information about each park, view additional images, and see the park's location on a map. This app leverages the power of the National Parks API to provide up-to-date and comprehensive information, making it easy for users to plan their next adventure.

- Developer: Noah Russell
- Development Time: Approximately 3 hours
- Technologies Used: Swift, SwiftUI, Xcode, National Parks API

## Features

The following required features have been successfully implemented:

- [✅] View National Parks List: Users can view a list of parks fetched from the National Parks API, with each park displaying basic information such as its name, description, and location.
- [✅] Park Detail Screen: Tapping on a park shows a detailed screen with additional information, images of the park, and an interactive map that showcases the park’s location.

## Optional Features

The following optional features were planned but not yet implemented:

- [❌] State Filter: Users can select a state from a menu to view only parks located in the selected state.
- [❌] Park Sorting: Allow users to sort parks alphabetically, either ascending or descending.
- [❌] Park Search: Provide a search bar to allow users to search for parks by name.

## Future Enhancements

In future versions, I plan to implement the following features to enhance user experience:

- [🔲] State Filter: Implement a drop-down menu or picker to filter parks based on the selected state.
- [🔲] Park Sorting: Enable users to sort the parks list alphabetically, both in ascending and descending order.
- [🔲] Park Search: Add a search bar to allow users to search for parks by name or keyword.
- [🔲] User Favorites: Allow users to mark parks as favorites and easily access them from a "Favorites" list.

## Video Walkthrough

Here’s a demonstration of the current functionality in the app:

<img style="max-width:300px;" src="Parks/Lab5.gif" alt="Parks App Demo">
GIF created with VEED.io.

## Development Process

This project was a great exercise in working with SwiftUI and integrating data from a REST API (the National Parks API). Here are some highlights:

- Data Fetching: The app retrieves data from the National Parks API and displays it in a list. This was accomplished using URLSession for fetching data and Decodable to parse the JSON response into usable models.
- SwiftUI Views: The app’s UI was built using SwiftUI, allowing for a responsive and clean interface. List and NavigationLink were used to display the list of parks and allow navigation to detailed park views.
- Map Integration: The detail screen includes an interactive map that uses MapKit to display the park’s location, providing users with visual context for where each park is located.

## Challenges Faced
- API Integration: The biggest challenge was understanding the structure of the National Parks API and ensuring that data was fetched and displayed correctly.
- UI Layout: Ensuring that the detail screen, images, and map were displayed correctly on all screen sizes and devices required some trial and error with layout constraints in SwiftUI.

## Key Takeaways
- Gained experience working with REST APIs in SwiftUI.
- Learned how to fetch and display data asynchronously using URLSession and Combine.
- Improved skills in MapKit for displaying maps in mobile applications.

## Technologies Used

- Programming Language: Swift
- Frameworks: SwiftUI, MapKit, UIKit (for some views), URLSession
- API: National Parks API
- Development Environment: Xcode 14.0+
- Version Control: Git, GitHub

## License

Parks is licensed under the Apache License 2.0.
You may obtain a copy of the license at:
http://www.apache.org/licenses/LICENSE-2.0
