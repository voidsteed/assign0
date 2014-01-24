assign0 explaination
=======
When I open the app, it showed me the onCreate() method is called to launch the app's activity, then onStart() called 
second, at last the onResume(). So the android activity is running now.

When I rotated the screen of my device, onPause(), onStop() and onDestroy() is called, so the vertical screen activity is 
shut down.
Then the setting of gravity changed to horizontal. It called the onCreate(), onStart and onResume to start another activity
that is the horizontal screen display the hello world.
