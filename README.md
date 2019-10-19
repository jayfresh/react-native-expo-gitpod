# React Native prototype on GitPod

This repo demonstrates running Expo CLI in GitPod. Just open this repo in GitPod and it will
start an Expo dev server that you can connect to using the Expo app running on a phone.

Click to open in GitPod: https://gitpod.io/#https://github.com/jayfresh/react-native-expo-gitpod

If you shut the Expo server down, you can run the app using `npm start` as this defaults `expo start`
to use the `tunnel` host parameter, which means the Expo mobile app can connect using a non-localhost URL
(since this is running in a remote VM).