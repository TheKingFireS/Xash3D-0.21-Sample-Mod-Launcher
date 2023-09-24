# Xash3D-0.21-Sample-Mod-Launcher
New Sample android project for mod.
# The things that need to be edit:
## To change the project name:
``android/settings.gradle`` and change ``rootProject.name = 'SampleProjectName'``
## To change the app name:
``android/app/src/main/res/values/strings.xml`` and change ``<string name="app_name">SampleAppName</string>``
## To change the package name:
``android/app/build.gradle`` and change both ``namespace 'su.xash.SamplePackageName'`` and ``applicationIdSuffix 'SamplePackageName'`` \
``android/app/src/main/java/su/xash/SamplePackageName/MainActivity.java`` and change folder name ``SamplePackageName/`` and change ``package su.xash.SamplePackageName;``
## To change game directory:
``android/app/src/main/java/su/xash/SamplePackageName/MainActivity.java`` and check 41 line or ``("gamedir", "SampleName")``
## To change app's icons:
Check ``android/app/src/main/res/mipmap-*dpi``
# Credit
Velaron for his TF15-Client's android folder. https://github.com/Velaron/tf15-client
