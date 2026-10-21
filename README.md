# Adaptive Notes

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![i18n](https://img.shields.io/badge/i18n-uk%20%7C%20en-0057B7?style=flat-square)

A notes app that adapts to the screen: a single-pane flow on phones and a **list-detail layout on tablets**, chosen with Material 3 **window size classes**. Strings are localized in **Ukrainian and English**, and UI elements have accessibility descriptions for screen readers.

> Lab #10 · Mobile Application Development course. Ukrainian version: [README.uk.md](README.uk.md)

## Features

- `calculateWindowSizeClass` picks `NotesPhoneLayout` or `NotesTabletLayout`
- Localized resources in `values-uk` and `values-en`
- `contentDescription` on interactive elements for TalkBack

## Tech stack

Kotlin · Jetpack Compose · Material 3 window size classes · Android resources localization

## Run locally

Open in Android Studio, let Gradle sync, run on a phone and on a tablet emulator to compare layouts.
