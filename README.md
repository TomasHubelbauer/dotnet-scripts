# `dotnet script` Tool

It is possible to run C# scripts by installing the `dotnet-script` tool:

`dotnet tool install -g dotnet-script`

To use it as a REPL, do `dotnet script`.

To use it to run a CSX file, do `dotnet script file.csx`.

To reference a NuGet package, add `#r "nuget: System.Drawing.Common, 4.5.1"`.

To load another script into the context of the current one, use `#load`.

To enable IntelliSense in VS Code, do `dotnet script init` to get the OmniSharp config and the debugger config.

## To-Do
