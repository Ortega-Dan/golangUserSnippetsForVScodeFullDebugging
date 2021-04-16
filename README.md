# golangUserSnippetsForVScodeFullDebugging

Copy all the contents of jsonc.json into the jsonc.json file of the User Snippets configuration.

Then create the following files:\
.vscode/launch.json\
.vscode/settings.json\
.vscode/tasks.json (Optional required if willing to run Golang code that has CLI functionality)


on each of them type "go" followed by part of the name of the file:\
e.g. to autopopulate the config for the settings.json file type "gosett" then hit enter\
(then adjust format if you want it)


Note: Two options are presented for launch.json. One for an improved basic launcher that works with the "Debug Console", and another for Golang code that has CLI functionality (which requires the tasks.json file with the corresponding snippet and works with the integrated terminal)
