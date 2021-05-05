# Unity Template - URP

**A template to start a Unity project with the latest beta version and the URP rendering pipeline.**

It already has :
- gitignore configured.
- git lfs set up with gitattributes.
- Editor configuration configured for C# writing conventions.
- Auto format on push, using github Actions and dotnet-format.
- The Unity project into a subfolder, with the starting packages for URP (including Shader Graph).
- New input system basic layout set-up.

I keep this project updated with the latest beta version (or official version if there is no beta).

## How to start a project from this template ?

To start a new project using this template, you can either pull this repo and change the remote to your own (That keep the git history), or you can also press the "Use this template" feature of Github (This will squash all the commits into a unique "Start project" commit).

I recommend tweaking a few things after starting a project : 
- Remove the UNLICENSE file, and add your own (usually under LICENSE)
- Describe your own project inside the README.md
- Rename the Unity_project folder into something more recognisable in the Unity Hub, such as ProjectName_Project. If you do so, you also need to mirror this change inside .github/workflows/linter.yml

With this, you are all set !

## Unlicense

This template is released into public domain. See the [UNLICENSE](./UNLICENSE) file.
