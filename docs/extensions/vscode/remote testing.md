# Remote Testing

When testing a Language Server its common to just 
either run unit tests or check in the editor how the 
server behaves

However i wanted to run a process and also set
breakpoints to also know what the client is calling 
and sending easily, so for that we have to specify an 
address in the client configuration


https://stackoverflow.com/questions/64000616/creating-lsp-language-server-protocol-for-multiple-clients-using-rpc

https://stackoverflow.com/questions/40284523/connect-external-language-server-to-vscode-extension

https://stackoverflow.com/questions/73830670/connecting-to-language-server-over-websocket

https://stackoverflow.com/questions/66164972/vs-code-how-to-get-process-id-via-shell-command-in-launch-json

https://github.com/microsoft/vscode-extension-samples/blob/main/lsp-log-streaming-sample/client/src/extension.ts

https://stackoverflow.com/questions/51041337/vscode-language-client-extension-how-to-send-a-message-from-the-server-to-the


https://nodejs.org/api/child_process.html

https://stackoverflow.com/questions/31946015/capturing-child-process-spawnsync-or-execsync-stdout

https://vscode-docs.readthedocs.io/en/stable/extensions/testing-extensions/


## VSCode settings
In the folder .vscode/, the files `launch.json` and `tasks.json`
are relevant to setting up breakpoints


## Logging
Logging can be useful to check on the terminal, implement it

https://code.visualstudio.com/api/language-extensions/language-server-extension-guide#logging-support-for-language-server

