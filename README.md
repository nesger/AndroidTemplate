# AndroidTemplate
This is a template with proguardFiles for android project.

>Differ

Most differ with a new project is build.gradle file for app module

You can find some differ following:

1. shrinkResources value is true
2. minifyEnabled value is true
3. getDefaultProguardFile('proguard-android.txt') is instead of getDefaultProguardFile('proguard-android-optimize.txt')

For more details you can find answer in [official web](https://developer.android.com/studio/build/shrink-code.html?hl=zh-cn)

>Usage

1. Fork the repository to your repository.
2. Clone to your local machine. [Optional]
3. Change the project name and package name for your project.

If you use another libs, you need to add rules in proguard-rules.pro file.