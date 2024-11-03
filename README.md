# Tok Tik

Tok Tik is a video app like TikTok, using Clean Architecture, `VideoPlayerController`, and `ChangeNotifierProvider`.

## Important Note

The folder `assets/videos/` has been excluded from version control due to the size of the `.mp4` files. Please add your own videos in this directory to test the app.

### Video Naming Convention

For this app to work correctly, videos should follow a specific naming format, as the code iterates through videos in numerical order. Use names like:
1.mp4, 2.mp4, 3.mp4, ...

Ensure each file in `assets/videos/` has this format so the app can load them successfully.
