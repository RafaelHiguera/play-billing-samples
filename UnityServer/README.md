Unity: Google Play Billing Server Sample
=====================================================

This is the Node.js server in TypeScript that use Cloud Functions for the game TrivialKart in
[Unity](https://github.com/zkzhao333/play-unity-plugins/tree/master/GooglePlayPlugins/com.google.play.billing/Samples/TrivialKart)

# Deploy Backend Server

**Before deploying the backend server, you should make sure you've completed the steps to
[setup the Unity game with the Play Developer Console](https://github.com/zkzhao333/play-unity-plugins/blob/master/GooglePlayPlugins/com.google.play.billing/Samples/TrivialKart/README.md).**

1. Make sure you have installed Node.js, npm, and [Firebase CLI](https://firebase.google.com/docs/cli/)

2. When you run `firebase init` make sure you select **Functions**, **TypeScript** and **Do not overwrite any file**

3. Then go to `cd functions` and run `npm install`

4. Run `firebase deploy` to deploy your server to Cloud Functions for Firebase
