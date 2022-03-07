This file explains the steps to create a unit test project using Visual code

# Process followed
* Install Visual Code
* Add [C# IntelliSence Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp) for better productivity
* Create the solution file using `dotnet new sln`
* Create Unit Test Project using `dotnet new mstest -o TheTest`
* Adding the Test Project to the solution using `dotnet sln add TheTest/TheTest.csproj`
* Execute the test using `dotnet test TheTest/TheTest.csproj`


---
# Referrence Link
The document available in the following link has been used [Test a .NET class library using Visual Studio Code - Using Unit Test](https://docs.microsoft.com/en-us/dotnet/core/tutorials/testing-library-with-visual-studio-code?pivots=dotnet-6-0)
