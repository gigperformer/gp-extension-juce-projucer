# GP Extension example for JUCE (with Projucer)

This is an example extension using the [Gig Performer SDK](https://github.com/gigperformer/gp-sdk).
You can use it as a base for your own extensions developed in with JUCE in C++ and built using the [Projucer](https://juce.com/discover/stories/projucer-manual).

**When cloning this project, remember to include the submodules!
For example, use `git clone --recurse-submodules ...` instead of `git clone ...`.**

## How to build...

### ... on macOS

-   Make sure you have [JUCE](https://juce.com) installed.
-   Open the `HelloGP-JUCE.jucer` project in Projucer.
-   Click _Save project_ to generate all the project files.
-   Open your project in Xcode and build it.
-   Copy the generated library to `/Users/Shared/Gig Performer/Extensions/`.

### ... on Windows

-   Make sure you have [Git](https://git-scm.com) and a C(++) compiler installed.
    You can get that for example by installing [Visual Studio](https://visualstudio.microsoft.com) with the _Desktop development with C++_ workload and the _Git for Windows_ component.
-   Make sure you have [JUCE](https://juce.com) installed.
-   Open the `HelloGP-JUCE.jucer` project in Projucer.
-   Click _Save project_ to generate all the project files.
-   Open your project in Visual Studio and build it.
-   Copy the generated library to `C:\Users\Public\Documents\Gig Performer\Extensions\`.
