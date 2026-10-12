# MapMaker

## Setup
After installing Enter project settings and go to/add a setting Called ```fatemap/project_directory```.
Set it's file path to the root folder of the project you are creating maps for.
![Project settings image](images/mapmaker_projectsetting_targetproject.png)
Make sure your target project has been set up as well. [setting up a project](maploader.md#setup)

### Map files

The mapmaker is meant as a frontend to creating/modifying maps ```.FMPE``` files. A compiled map becomes a ```.fatemap``` and is a different format.
```.FMPE``` files keep the full data and are a larger file size than ```.fatemap``` files. ```.fatemap``` files remove unneeded data that is only required during editing to reduce load time and file size.