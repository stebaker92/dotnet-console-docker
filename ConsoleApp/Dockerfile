FROM microsoft/dotnet:2.0-runtime
WORKDIR /app
ADD bin/Debug/netcoreapp2.0/publish/ ./
ENTRYPOINT ["dotnet", "./ConsoleApp.dll"]
