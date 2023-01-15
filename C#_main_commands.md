# C# basics

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

## Basic commands
- Console.WriteLine("text"); - to display something with a new line
- Console.Write("text"); --> to display something in one line 
- Console.ReadLine(); - reads data. But it is necessary to store this data somewhere --> take care of data type
- new Random().Next(min, max); --> gives a random integer from min to max-1 #int number = new Random().Next(1, 10);
- string username = Console.ReadLine(); --> to read the data that user entered
- username.ToLower() --> letters case will not affect
- Console.Clear(); --> cleans console
- Console.SetCursorPosition(10, 4); --> puts symbols per required coordinates by indicated distance from left and right sides
- int.Parse(Console.ReadLine()); & Convert.ToInt32(Console.ReadLine()); --> to read and convert the value into integer
- Console.WriteLine($"text {number} text {result}"); & Console.WriteLine("text {0} text {1}", number, result); & Console.WriteLine("text " + number + " text " + result); --> to display the result into one line

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

## Methods (Functions)
- Convert.ToInt32(Math.Pow(number, 2)); --> exponentiation of number, set any figure instead of 2
- count++; --> to increase by 1
- return --> returns result
- break --> stop running
- int Max(int arg1, int arg2, int arg3) --> find max
- PrintArray(int[] array); --> show index in array
- void --> does not return result
- new Random().Next(1, 10); --> to fill with random numbers from 1 to 10
- FillArray(array); --> fill array
- PrintArray(array); --> to display array

## Arrays
- int [] array = {..., ..., ...}; --> to define array
- array[0] = 12; --> to write value in the array index
- Console.WriteLine(array[4]); --> to display the value stored by index 4
- array.Length; --> define length of array
- int[] array = new int[10]; --> to create a new array and give its size - 10. By default it is filled with 0
- void FillArray(int[] array) --> to fill array
- array[index] = new Random().Next(1, 10); --> to fill with random numbers from 1 to 10

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


! " ; " is important as it indicates end of command.

"\b\b   " if required to hide the last symbol, like , .

" // " to leave a comment which does not affect the code (ctrl + /)

