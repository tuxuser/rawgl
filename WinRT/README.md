# Another World - WinRT / UWP

## Build from source

### Requirements

* Visual Studio 2019
* VS needs UWP / WinRT support support enabled

### Clone the repo and its dependencies

```
git clone https://github.com/tuxuser/rawgl.git
git checkout winrt
git submodule update --init --recursive
```

### Visual studio build
* Copy Another World gamedata to data/ directory (setup.dat without a subfolder)
* Open <REPO>/WinRT/AnotherWorld.sln in Visual Studio
* Right-click on "SDL2-UWP" in "Solution Explorer", hit "Retarget projects", confirm with OK
* Build the project
* Deploy locally or to a remote device (Xbox One maybe?)
  
  NOTE: When deploying to Xbox One you need to be signed in with an account on the console.

## Required data files

Prior building, these files need to copied inside the project:

```
TODO
```
