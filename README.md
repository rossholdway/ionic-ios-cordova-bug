#Cordova 4.0.0 / 4.0.1 and Ionic 1.2.4 bug

To reproduce clone the repo and run `bower install`, `ionic state restore` and `ionic build ios`.

Running the app on an actual iOS 9.2 or 9.3 (beta2) device will cause it to freeze on launch.

See [https://github.com/driftyco/ionic/issues/5318](https://github.com/driftyco/ionic/issues/5318) for more info.