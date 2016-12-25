# UE4 Project Build Scripts

## Windows
### Set up
Change *Helpers/GetProjectPath.cmd* to return path to your project

For example, if you move content of *Windows* directory to your project dir (e.g. in %projectDir%/Script), content of *Helpers/GetProjectPath.cmd* should be

`@echo ..\`

### Usage
Then you can run:

*GenerateProjectFiles.cmd* to generate VS project files for your project

*CompileDll.cmd* to compile DLL needed to run project in editor

*CookBinaries.cmd* to cook game into windows standalone game (all files needed to run game will be in %projectDir%\Artifacts)
