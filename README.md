# AwesomePlaces

This is my first mobile application. You will notice that not much is in here; shortly after starting a guided course, a myriad of environment issues came up. While the build occasionally successfully completes via Android studio, 99% of the time it crashes due to a handful of errors, with the most common one being: 
```
> Task :app:installDebug FAILED

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':app:installDebug'.
> com.android.builder.testing.api.DeviceException: No connected devices!

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

Deprecated Gradle features were used in this build, making it incompatible with Gradle 5.0.
Use '--warning-mode all' to show the individual deprecation warnings.
See https://docs.gradle.org/4.10.1/userguide/command_line_interface.html#sec:command_line_warnings

BUILD FAILED in 16s
26 actionable tasks: 6 executed, 20 up-to-date
Could not install the app on the device, read the error above for details.
Make sure you have an Android emulator running or a device connected and have
set up your Android development environment:
https://facebook.github.io/react-native/docs/getting-started.html
```