## php-cgi-spawner

It is the smallest (less than 4kb) and the easiest way to spawn a multiple php-cgi proccesses in Windows for your nginx server with fastcgi.

- It spawns as many php-cgi on a port as you need.
- It automatically restarts them if they crashed.

## Build

Run [make.bat](src/make.bat) in a Visual Studio environment.

## Example

The [example](example) directory contains [php-cgi-spawner.exe](example/php-cgi-spawner.exe) (compiled in Visual Studio 2008 for successfully run on Windows XP) and scripts to [run](example/_php-cgi-nginx-restart.bat) and [stop](example/_php-cgi-nginx-stop.bat) your web server.
