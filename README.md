# CSharp

C:\Windows\Microsoft.NET\Framework64\v4.0.30319\csc.exe Files.cs    

mcs -out:hello.exe hello.cs
mono hello.exe


Hello World:

https://www.geeksforgeeks.org/hello-world-in-c-sharp/


_________________________________________________________________________

For Linux:

Check Version:


pi@raspberrypi:~ $ cat /etc/os-release

PRETTY_NAME="Raspbian GNU/Linux 10 (buster)"

NAME="Raspbian GNU/Linux"

VERSION_ID="10"

VERSION="10 (buster)"

VERSION_CODENAME=buster

ID=raspbian

ID_LIKE=debian

HOME_URL="http://www.raspbian.org/"

SUPPORT_URL="http://www.raspbian.org/RaspbianForums"

BUG_REPORT_URL="http://www.raspbian.org/RaspbianBugs"

pi@raspberrypi:~ $ 
____________________________________________________________________________________________________________________________________________________

sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 3FA7E0328081BFF6A14DA29AA6A19B38D3D831EF

echo "deb http://download.mono-project.com/repo/debian wheezy main" | sudo tee /etc/apt/sources.list.d/mono-xamarin.list

sudo apt-get update

sudo apt-get install mono-complete

nano hello.cs


Write CSharp And Compile by the Command Above
_________________________________________________________________________________________________

mcs: references the 4.0-profile libraries (the APIs as defined in .NET 4.0) and supports C# 4.0.

gmcs: references the 2.0-profile libraries (the APIs as defined in .NET 2.0 and .NET 3.5) and exposes the full C# 3.0 language.

smcs: references the 2.1-profile libraries (the APIs defined for Silverlight) and exposes the full C# 3.0 language. This is the compiler used for creating Silverlight/Moonlight applications.



https://kozmicluis.com/compile-c-sharp-command-line/
_____________________________________________________________________________________________________________________________________________________

Compile C# without Visual Studio:

Windows:

C:\WINDOWS\Microsoft.NET\Framework\v[your version number]\csc.exe


C:\Users\user\Desktop\forbes>C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\csc.exe Files.cs

Microsoft (R) Visual C# Compiler version 4.8.3752.0

for C# 5

Copyright (C) Microsoft Corporation. All rights reserved.

This compiler is provided as part of the Microsoft (R) .NET Framework, but only supports language versions up to C# 5, which is no longer the latest version. For compilers that support newer versions of the C# programming language, see http://go.microsoft.com/fwlink/?LinkID=533240

How to run C#:

Files.exe


__________________________________________________________________________________________________




https://stackoverflow.com/questions/861384/is-it-possible-to-install-a-c-sharp-compiler-without-visual-studio

https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/compiler-options/command-line-building-with-csc-exe#:~:text=The%20csc.exe%20executable%20file,configuration%20of%20a%20particular%20computer.


https://dotnet.microsoft.com/
