# DotnetHelloWorldWebapp_Sample

dotnet new sln -o HelloWorldApp
cd HelloWorldApp
dotnet new mvc -n HelloWorldApp.Web 
dotnet sln HelloWorldApp.sln add HelloWorldApp.Web\HelloWorldApp.Web.csproj
#cd HelloWorldApp.Web
#dotnet run
dotnet restore
dotnet build --no-restore --configuration release
dont publish --no-build --configuration release
