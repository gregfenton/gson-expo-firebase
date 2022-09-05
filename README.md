# To use this code:

1. `git clone https://github.com/gregfenton/gson-expo-firebase`
2. `npm install`  (must use `npm install` since Expo isn't installed yet)
3. Edit `App.js` to put your Firebase project's config values into `firebaseConfig`
4. Run the app with `npx expo start`

If you see a Date displayed in the UI (and no errors in the expo console), then it is working!  In the console you should see a log message similar to:
```
myApp is  {"_isDeleted":false,"_options":{"apiKey":"YOUR_API_KEY","authDomain":"YOUR_PROJECT_NAME.firebaseapp.com","databaseURL":"https://YOUR_PROJECT_NAME.firebaseio.com","projectId":"YOUR_PROJECT_NAME","storageBucket":"YOUR_PROJECT_NAME.appspot.com","messagingSenderId":"1234567890123","appId":"1:1234567890123:web:5aaaaabbbbbcccccd77","measurementId":"G-A6B4LLC2BL"},"_config":{"name":"[DEFAULT]","automaticDataCollectionEnabled":false},"_name":"[DEFAULT]","_automaticDataCollectionEnabled":false,"_container":{"name":"[DEFAULT]","providers":{}}}
```
