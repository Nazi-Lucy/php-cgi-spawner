# php-cgi-spawner
[![Build status](https://ci.appveyor.com/api/projects/status/6f2rqvltmp9ax4nd?svg=true)](https://ci.appveyor.com/project/deemru/php-cgi-spawner)

[php-cgi-spawner](https://github.com/deemru/php-cgi-spawner) is the smallest and easiest application to spawn a multiple php-cgi processes in Windows for your web server with fastcgi

- It spawns as many php-cgi on a port as you need
- It automatically restarts them if they crashed
- Example of 4 php-cgi on tcp/9000: php-cgi-spawner.exe php\php-cgi.exe 9000 4

# Download

Go to [release](https://github.com/deemru/php-cgi-spawner/releases/latest) to download the application

# Build

Go to [src](src) directory and run [make.bat](src/make.bat) in a Visual Studio environment

# Notice

Currently a maximum number of php-cgi processes is 64 because of MAXIMUM_WAIT_OBJECTS in WaitForMultipleObjects
