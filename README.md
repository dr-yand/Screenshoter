# Screenshoter
Screenshoter is a library for taking screenshots in your android applications

Include Screenshoter repository in your project's build.gradle file:
```
allprojects {
    repositories {
        google()
        jcenter()

        maven { url 'https://github.com/dr-yand/Screenshoter/raw/master/' }
    }
}
```

Then add the library in the dependencies block of the module's build.gradle file:
```
implementation "com.kritsin.screenshoter:Screenshoter:1.0@aar"
```

Now you can you Screenshoter:
```
Bitmap bitmap = Screenshoter.getScreenshot(<activity>)
```
