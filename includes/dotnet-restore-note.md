> [!NOTE]
> Ab .NET Core 2.0 müssen Sie [`dotnet restore`](~/docs/core/tools/dotnet-restore.md) nicht mehr ausführen, da der Befehl implizit von allen Befehlen, z.B. `dotnet build` und `dotnet run`, ausgeführt wird, die eine Wiederherstellung erfordern. In bestimmten Fällen eignet sich der Befehl dennoch. Dies ist etwa bei Szenarios der Fall, in denen das Ausführen einer expliziten Wiederherstellung sinnvoll ist. Beispiele hierfür sind [Continuous Integration-Builds in Visual Studio Team Services](/vsts/build-release/apps/aspnet/build-aspnet-core) oder Buildsystemen, die den Zeitpunkt für die Wiederherstellung explizit festlegen müssen.