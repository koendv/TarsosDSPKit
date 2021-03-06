This Android library is an easy way to use TarsosDSP Real-Time Audio Processing and Rubberband Real-Time Audio Time-Stretching in your Android app.
Just copy tarsosdspkit.aar to the libs directory of your app source tree. 

Downloads
---------
Pre-compiled .aar for Android: [TarsosDSPKit-release.aar](https://github.com/koendv/TarsosDSPKit/raw/master/binaries/TarsosDSPKit-release.aar). 

(There is also a 'debug' version, just in case: [TarsosDSPKit-debug.aar](https://github.com/koendv/TarsosDSPKit/raw/master/binaries/TarsosDSPKit-debug.aar).)

This library includes TarsosDSP and RubberBandJNI Java source, and executeables and shared libraries for 32-bit Arm, 64-bit Arm and 64-bit Intel.

Usage
-----
Download TarsosDSPKit-release.aar. Copy to your project as app/libs/TarsosDSPKit-release.aar 
Then in your project’s app/build.gradle add the following to your project's dependencies:

    dependencies {
        // other dependencies go here ...
        implementation fileTree(dir: 'libs', include: ['*.jar'])
        implementation fileTree(dir: 'libs', include: ['*.aar'])
    }

Compilation
-----------

The source is a packaging of [TarsosDSP](https://github.com/JorenSix/TarsosDSP) and [RubberBandJNI](https://github.com/JorenSix/RubberBandJNI) with binaries for arm, arm64 and x86-64 from [FFmpeg-Audio-Android](https://github.com/koendv/FFmpeg-Audio-Android) and [RubberBand-Android](https://github.com/koendv/rubberband). Applied patches are in the patches/ directory. 

Compiled with Android Studio 2.3.3. After compilation Android libraries are in app/build/outputs/aar/*.aar

