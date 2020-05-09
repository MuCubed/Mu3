**Infrastructure Plans**
These are some ideas I have as far as how an infrastructure could work. These are not set in stone, and will likely take some development time. (Once I even know I have content to work with.)

1. Build System
	- Should be able to clone this repo and download a specified Kik APK file and then run the build command
	- This will require some system to manipulate the APK to generate a new one

2. Release
	- Each release should be tagged and somehow reference a version of the Kik APK for which it is known to work
	- This means that as this project and Kik might go out of sync, we can at least have a known good building point
	
3. Updates
	- No one wants to search around for the latest version. Some modified Kik clients have an updater that will direct them to the latest APK
	- **We cannot distribute a compiled APK** nor can we condone others do so
	- I'd like to provide functionality for a user to save a URL that points to their own build server. That way they can directly update from their build server as new build become available.
	
4. Credits
	- Many modified Kik clients come with a credits page
	- A credits page for this project would likely parse the credits .txt files for each projects' directory and append them together somehow showing what everyone did