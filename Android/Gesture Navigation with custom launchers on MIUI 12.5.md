# How to use gesture navigation on MIUI 12.5 with custom launchers

1. Download and install [FNG - Fluid Navigation Gestures](https://play.google.com/store/apps/details?id=com.fb.fluid) app from Play Store.
    + Configure gestures.
    + Grant permissions, exclude from battery optymalization and lock to work in background. [Read More](https://dontkillmyapp.com/xiaomi)
2. Enter following command using ADB: `settings put global force_fsg_nav_bar 1`. - This will disable on-screen navigation bar.
    + You can use ADB without PC by using [LADB - Local ADB Shell](https://play.google.com/store/apps/details?id=com.draco.ladb) app. All you need is to be connected to wifi. 


`[i]` Keep in mind that you have to repeat step 2 after every restart
