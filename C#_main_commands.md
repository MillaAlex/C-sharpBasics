# C# commands

## Create new project
- git init
- open in integrated terminal -> dotnet new console --> prepares the console for a new project
- Program.cs -> enter/write the code
- git add Folder_name
- git commit -m "message"
- dotnet run -> runs the project / code
- git push origin main --> to upload to GitHub

### How to get rid of unnecessary files/folders
.gitignore --> create this file and there is ready file for dotnet on GitHub, just to copy & save & add & commit

! Take care of the files and terminals you're working in!

- symbol " // " - to leave a comment which does not affect the code

## Basic commands
- Console.WriteLine("text"); - to display something with a new line
- Console.Write("text"); --> to display something in one line 
- Console.ReadLine(); - reads data. But it is necessary to store this data somewhere --> take care of data type
- new Random().Next(min, max); --> gives a random integer from min to max-1 #int number = new Random().Next(1, 10);
- string username = Console.ReadLine(); --> to read the data that user entered
- username.ToLower() --> letters case will not affect
- Console.Clear(); --> cleans console
- Console.SetCursorPosition(10, 4); --> puts symbols per required coordinates by indicated distance from left and right sides

## If Condition
- if(username == "name")
{
        Console.WriteLine("text");
}
else
{
    Console.Write("text");
    Console.WriteLine(username);
}

## While cycle
int count = 0;
while(condition: count < 100>)
{
    actions
    count = count + 1 (count++  /  count +=1)
}


! " ; " is important as it indicates end of command.

## Data types
- int number --> integer (Z-numbers): range -2 147 483 648 +2 147 483 648 / 32-bit integer
- double number --> float number (R-numbers): even bigger range / 64-bit integer
- string stringname --> from 0 up to many symbols / from 4 bites up to 2 Gb
- bool --> true & false / 1 bite

## Classical math symbols
- " + " --> compounding
- " - " --> subtracting
- " / " --> division with integers
- " * " --> multiplication
- " % " --> remainder of division
- " () " --> changes priority of operations




