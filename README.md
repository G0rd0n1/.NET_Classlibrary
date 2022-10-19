# .NET_Classlibrary
Microsoft .NET class library using Visual Studios for Quality Assurance

## Introduction
In this project, I created a solution, added a library project, and added a console app project that uses the library.

I started working with the .NET class library. It is my first time tackling Quality Assurance but so far I have enjoyed the introduction and hope to continue working on improvements within this project and further projects.

## Create a Solution

Started off by creating a blank solution to put the class library project into. From what I have seen the solution serves as a container for one or more projects. 'ClassLibraryProjects' is the folder in which the class library project is located.

## Create a class library project

I created a new .NET class library project named 'StringLibrary' to the solution.

The class library I'm using contains a 'UtilityLibraries.StringLibrary' which has a method called 'StartsWithUpper'.
This method returns:
                    True - if the string starts with an upper case letter.
                    False - if the string starts with a lower case letter.

(1) The Unicode standard distinguishes uppercase characters from    lowercase characters.
(2) The Char.IsUpper(Char) method returns true if a character is uppercase.

## Add a console app to the solution

I Added a console application that uses the class library. The app will prompt the user to enter a string and report whether the string begins with an uppercase character or not.

I also opened the 'Program.cs' and replaced all of the code with the appropriate cs code in order for us to get the intended results.

## Add a project reference

Initially, the new console app project doesn't have access to the class library. To allow it to call methods in the class library, create a project reference to the class library project.

## Run the project

In order to run the project and get an idea of the project, you first have to make sure that you are in the working directory[ClassLibraryProjects]. 
From there you run: [ 'dotnet run --project ShowCase/ShowCase.csproj' ]
Type random words and press enter to get a response.