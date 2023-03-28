# 1. Project overview

## (1)App Features

This app is able to use below function.

- User can see Hello, world.

## (2)Project Structure

```zsh
% tree -L 3
.
├── README.md
├── analysis_options.yaml
├── android
│   ├── app
│   │   ├── build.gradle
│   │   └── src
│   ├── build.gradle
│   ├── flutter_helloworld_android.iml
│   ├── gradle
│   │   └── wrapper
│   ├── gradle.properties
│   ├── gradlew
│   ├── gradlew.bat
│   ├── local.properties
│   └── settings.gradle
├── assets
│   └── icon.png
├── build
│   ├── 45886b142bc145892b759f94884454f6
│   │   ├── _composite.stamp
│   │   ├── gen_dart_plugin_registrant.stamp
│   │   └── gen_localizations.stamp
│   ├── app
│   │   ├── generated
│   │   ├── intermediates
│   │   ├── kotlin
│   │   ├── outputs
│   │   └── tmp
│   ├── c075001b96339384a97db4862b8ab8db.cache.dill.track.dill
│   ├── ios
│   │   ├── Debug-iphoneos
│   │   ├── Debug-iphonesimulator
│   │   ├── app-delta
│   │   ├── iphoneos
│   │   └── iphonesimulator
│   ├── kotlin
│   │   └── sessions
│   └── macos
│       ├── Build
│       ├── Logs
│       ├── ModuleCache.noindex
│       └── info.plist
├── flutter_helloworld.iml
├── ios
│   ├── Flutter
│   │   ├── AppFrameworkInfo.plist
│   │   ├── Debug.xcconfig
│   │   ├── Generated.xcconfig
│   │   ├── Release.xcconfig
│   │   └── flutter_export_environment.sh
│   ├── Runner
│   │   ├── AppDelegate.swift
│   │   ├── Assets.xcassets
│   │   ├── Base.lproj
│   │   ├── GeneratedPluginRegistrant.h
│   │   ├── GeneratedPluginRegistrant.m
│   │   ├── Info.plist
│   │   └── Runner-Bridging-Header.h
│   ├── Runner.xcodeproj
│   │   ├── project.pbxproj
│   │   ├── project.xcworkspace
│   │   └── xcshareddata
│   └── Runner.xcworkspace
│       ├── contents.xcworkspacedata
│       └── xcshareddata
├── lib
│   └── main.dart
├── linux
│   ├── CMakeLists.txt
│   ├── flutter
│   │   ├── CMakeLists.txt
│   │   ├── generated_plugin_registrant.cc
│   │   ├── generated_plugin_registrant.h
│   │   └── generated_plugins.cmake
│   ├── main.cc
│   ├── my_application.cc
│   └── my_application.h
├── macos
│   ├── Flutter
│   │   ├── Flutter-Debug.xcconfig
│   │   ├── Flutter-Release.xcconfig
│   │   ├── GeneratedPluginRegistrant.swift
│   │   └── ephemeral
│   ├── Runner
│   │   ├── AppDelegate.swift
│   │   ├── Assets.xcassets
│   │   ├── Base.lproj
│   │   ├── Configs
│   │   ├── DebugProfile.entitlements
│   │   ├── Info.plist
│   │   ├── MainFlutterWindow.swift
│   │   └── Release.entitlements
│   ├── Runner.xcodeproj
│   │   ├── project.pbxproj
│   │   ├── project.xcworkspace
│   │   └── xcshareddata
│   └── Runner.xcworkspace
│       ├── contents.xcworkspacedata
│       └── xcshareddata
├── pubspec.lock
├── pubspec.yaml
├── test
│   └── widget_test.dart
├── web
│   ├── favicon.png
│   ├── icons
│   │   ├── Icon-192.png
│   │   ├── Icon-512.png
│   │   ├── Icon-maskable-192.png
│   │   └── Icon-maskable-512.png
│   ├── index.html
│   └── manifest.json
└── windows
    ├── CMakeLists.txt
    ├── flutter
    │   ├── CMakeLists.txt
    │   ├── generated_plugin_registrant.cc
    │   ├── generated_plugin_registrant.h
    │   └── generated_plugins.cmake
    └── runner
        ├── CMakeLists.txt
        ├── Runner.rc
        ├── flutter_window.cpp
        ├── flutter_window.h
        ├── main.cpp
        ├── resource.h
        ├── resources
        ├── runner.exe.manifest
        ├── utils.cpp
        ├── utils.h
        ├── win32_window.cpp
        └── win32_window.h

58 directories, 74 files
```

# 2. Requirements

```zsh
% flutter --version
Flutter 3.7.6 • channel stable • https://github.com/flutter/flutter.git
Framework • revision 12cb4eb7a0 (7 days ago) • 2023-03-01 10:29:26 -0800
Engine • revision ada363ee93
Tools • Dart 2.19.3 • DevTools 2.20.1
```

## (1)Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
