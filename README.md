# 010 Editor Template for MLV files

## Purpose
The purpose of this project is to create a MLV Template for the [010 Editor](https://www.sweetscape.com/010editor/), a binary text editor. 010 Editor allows the use of Templates to parse binary files and make sense of the data. This aids in understanding the structure of the file and quickly extracting needed information directly from the binary file. 010 Editor also allows you to make changes to the file.

## Goal
The goal of this project is to translate the information provided in the [MLV App repo](https://github.com/ilia3101/MLV-App) into a Template. Suggested sources for primary information is in [mlv.h](https://github.com/ilia3101/MLV-App/blob/master/src/mlv/mlv.h) and [mlv_object.h](https://github.com/ilia3101/MLV-App/blob/master/src/mlv/mlv_object.h).

## Resources
The [010 Editor](https://www.sweetscape.com/010editor/) Template language is very similar to C/C++, so for the most part this Template is developed by copy/pasting the code from [mlv.h](https://github.com/ilia3101/MLV-App/blob/master/src/mlv/mlv.h) and [mlv_object.h](https://github.com/ilia3101/MLV-App/blob/master/src/mlv/mlv_object.h) and tweaking it to match 010's syntax. This [video series](https://github.com/diyinfosec/YT_Exercises/tree/master/Building_Templates_for_010Editor) by [diyinfosec](https://www.youtube.com/channel/UC-a2-ZW4_CzkBsbk3boJoWQ) is a good crash course on 010 Templates.

## Code
[MLV.bt](https://github.com/tdnelson2/MLV_010_Editor_Template/blob/main/MLV.bt) is the Template file. A MLV file, [M13-1828.MLV](https://github.com/tdnelson2/MLV_010_Editor_Template/blob/main/M13-1828.MLV) is included for convenience. 