# Sodium

Follow the steps below in order to download Sodium source code 

* If you do not have `git` installed on your system. Download it from https://git-scm.com/download/win

* Open a new console window. (Press `Start + R` and type the command below then click Ok.)

  `cmd`

* Move to root directory of `C:` drive

   `cd c:\`
  
* Run the command below to download all Sodium projects at once. (If you want to install Sodium into different folder name other than `c:\Sodium`, you need to change many project settings)

  `git clone --recursive https://github.com/muradkarakas/Sodium.git`
   
* Find and open C:\Sodium\Sodium.sln file with Visual Studio.

* In order to make full compile, you must download and install a few more applications listed below. (Download 64Bit version)

  * Oracle Database Express Edition (XE)
  * PostgreSQL 
  * MySql Database Server
  * MS Sql Server
  * Redis Server

* Add `C:\Sodium\Sodium-Setup` path to the system `PATH` environment variable.

* Run Visual Studio as administrator. Then find and open `c:\Sodium\Sodium.sln` solution file.

* Maybe you need to modify some project settings according to database library path.
