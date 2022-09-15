On Windows 10 + Powershell

```ps
$ npm test

> test
> ts-node test.ts

The argument '/C/Users/rp/AppData/Local/Temp/test-a99da100.sh' is not recognized as the name of a script file. Check the spelling of the name, or if a path was included, verify that the path is correct and try again.

Usage: pwsh[.exe] [-Login] [[-File] <filePath> [args]]
                  [-Command { - | <script-block> [-args <arg-array>]
                                | <string> [<CommandParameters>] } ]
                  [-ConfigurationName <string>] [-CustomPipeName <string>]
                  [-EncodedCommand <Base64EncodedCommand>]
                  [-ExecutionPolicy <ExecutionPolicy>] [-InputFormat {Text | XML}]
                  [-Interactive] [-MTA] [-NoExit] [-NoLogo] [-NonInteractive] [-NoProfile]
                  [-OutputFormat {Text | XML}] [-SettingsFile <filePath>] [-SSHServerMode] [-STA]
                  [-Version] [-WindowStyle <style>] [-WorkingDirectory <directoryPath>]

       pwsh[.exe] -h | -Help | -? | /?

PowerShell Online Help https://aka.ms/powershell-docs

All parameters are case-insensitive.
$ npx ts-node test.ts
works
```
