# Little Lemon Food Ordering App

- The application is a React Native Expo Food app.
- Users will be capable of signing up on the Little Lemon restaurant app.
- Users will have to go through a registration process.
- Once they successfully complete that phase, they are redirected to a home screen.
- Home screen will represent the landing screen after completing the onboarding flow, displaying a header, a banner with a search bar and a list of menu items where a user can filter each categories.
- User can also customize their name, email, photo and and other user preferences through a Profile Screen.
- Profile screen also contains four checkboxes enable specific email notifications, like order status, password changes,special offers, and newsletters.
- Use AsyncStorage module to preserve the chosen preferences even when the user quits the application
- When clicking the Logout button, user will redirect back to login page, clearing all data saved from Profile.
- Use SQLite Database to populate, query and filter menu items.



### How to use the project

##### npm install && npm start
##### Then, a QR Code wil appear on your terminal.
##### On IOS Scan QR code through Camera app.
##### On Android : Scan QR code through Expo Go app.


### Screenshot
![final_mockup](https://user-images.githubusercontent.com/108392678/217717918-a6f83c94-c1ab-4796-903e-388b9a67cdd9.jpg)
![Onboarding](https://user-images.githubusercontent.com/108392678/217715066-19026169-ab51-450e-b21c-cc925940d03e.jpg)
![Profile and Home](https://user-images.githubusercontent.com/108392678/217715079-d66eb960-f5cf-4cdf-8f33-b45b320fca7e.jpg)



### Built with

- [React Native](https://reactnative.dev/docs/environment-setup) - React Native app built with expo
- [SQLite](https://docs.expo.dev/versions/latest/sdk/sqlite/) - For storing restaurant's menu items.
- [AsyncStorage](https://react-native-async-storage.github.io/async-storage/docs/api/) - For storing user preferences.
- [StyleSheet](https://reactnative.dev/docs/stylesheet) - For styles

### What I learned

- Create a React Native App using Expo
- Create a wireframe and high fidelity mockup using Figma.
- Use ContextAPI for login
- Use React Navigation (Native Stack) for screen routes.
- Use ImagePicker API to set user Profile Picture
- Use useFonts Hook from expo-fonts to set custom fonts
- Use AsyncStorage to store user settings.
- Use getItem and setItem methods to read and set data to AsyncStorage
- ConnectAsyncStorage to a state
- Use SQLite to store Menu Items
- Connect SQLite to a state
- Create form validation for users
- Handling side-effects using useEffect Hook
- Use FlatList component to render menu
- Use ScrollView component to render categories title
- Use View, View, Text Components
- Extract all styles to StyleSheet API

## Author

- LinkedIn - [@princechhirolya](https://www.linkedin.com/in/princechhirolya/)
- Twitter - [@pr_chhhirolya](https://www.twitter.com/pr_chhirolya)
