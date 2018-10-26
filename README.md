This Android library is an easy way to use TarsosDSP Real-Time Audio Processing and Rubberband Real-Time Audio Time-Stretching in your Android app.
Just copy tarsosdspkit.aar to the libs directory of your app source tree. 

Downloads
---------
Pre-compiled .aar for Android: [TarsosDSPKit-release.aar](https://raw.githubusercontent.com/koendv/TarsosDSPKit/blob/master/binaries/TarsosDSPKit-release.aar)

This library includes TarsosDSP and RubberBandJNI Java source, and executeables and shared libraries for 32-bit Arm, 64-bit Arm and 64-bit Intel.

Compilation
-----------

The source is a packaging of [TarsosDSP] (https://github.com/JorenSix/TarsosDSP) with binaries for arm, arm64 and x86-64 from [FFmpeg-Audio-Android](https://github.com/koendv/FFmpeg-Audio-Android) and [RubberBandJNI]( https://github.com/JorenSix/RubberBandJNI) with  binaries for arm, arm64 and x86-64 from (RubberBand-Android)[https://github.com/koendv/rubberband]. Applied patches are in the patches/ directory. 

Compiled with Android Studio 2.3.3. After compilation Android libraries are in app/build/outputs/aar/*.aar
