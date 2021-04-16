# golangUserSnippetsForVScodeFullDebugging

Copy all the contents of jsonc.json into the jsonc.json file of the User Snippets configuration.\
![](readmeImages/step1.png)\
then ...\
![](readmeImages/step2.png)



Then create the following files:\
.vscode/launch.json\
.vscode/settings.json\
.vscode/tasks.json (Optional required if willing to run Golang code that has CLI functionality)


On each of those files type "go" followed by part of the name of the file (to filter the options).\
E.g. To auto populate the config for the settings.json file type "gosett", then hit enter\
(then adjust format if you want it)
![](readmeImages/step3.png)

**Note:** Two options are presented for launch.json.\
One for an improved basic launcher that works with the "Debug Console", and another for Golang code that has CLI functionality (which requires the tasks.json file with the corresponding snippet and works with the integrated terminal).
