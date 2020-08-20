Unity: Google Play Billing Server Sample
=====================================================

This is the Node.js server in TypeScript that use Cloud Functions for the game TrivialKart in
[Unity](https://github.com/zkzhao333/play-unity-plugins/tree/master/GooglePlayPlugins/com.google.play.billing/Samples/TrivialKart)

# Deploy Backend Server

**Before deploying the backend server, you should make sure you've completed the steps to
[setup the Unity game with the Play Developer Console](https://github.com/google/play-unity-plugins/tree/master/GooglePlayPlugins/com.google.play.billing/Samples/TrivialKart/README.md).**

**Also make sure to replace the placeholderKey in the keys folder with your own key. This is a tutorial that shows how to do it : [Generate Key](https://medium.com/androidhub/how-to-validate-in-app-purchase-subscription-on-your-node-js-backend-a2b823470034).**

1. Make sure you have installed Node.js, npm, and [Firebase CLI](https://firebase.google.com/docs/cli/)

2. When you run `firebase init` make sure you select **Functions**, **TypeScript** and **Do not overwrite any file**

3. Then go to `cd functions` and run `npm install`

4. Check in the **package.json file** that the **engines and dependencies arrays** have the latest version for each package

5. Run `firebase deploy` to deploy your server to Cloud Functions for Firebase

# Useful information

**This sever use [google-play-billing-validator](https://www.npmjs.com/package/google-play-billing-validator)**

**The flow of the [Purchase verification](https://docs.unity3d.com/Manual/UnityIAPProcessingPurchases.html)**

**[Google Play Developer API](https://developers.google.com/android-publisher)**
