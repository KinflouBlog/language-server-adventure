# Building the Language Client

keep in mind for the extension workflow:
 - create watchers to watch for changes in the workspace
 - start the language server for each file


keep in mind for the language server handling workflow:
 - find language server binary for local search
 - download language server binary if not found
 - try to find language server instance for local and remote address
 - 

## Output Channel
The output channel is a good feature for outputing logs in a 
select way for different things, it can even have custom syntax
coloring by proving a language id

https://code.visualstudio.com/updates/v1_66#_output-channel-with-custom-language-id

https://code.visualstudio.com/api/references/vscode-api#OutputChannel
