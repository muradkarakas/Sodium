# Sodium Source Download

Follow the steps below in order to download Sodium source code 

* If you do not have `git` installed on your system. Download it from https://git-scm.com/download/win

* Open a new console window. (Press `Start + R` and type the command below then click Ok.)

  `cmd`

* Move to root directory of `C:` drive

   `cd c:\`
  
* Run the command below to download all Sodium projects at once. (If you want to install Sodium into different folder name other than `c:\Sodium`, you need to change many project settings)

  `git clone --recursive https://github.com/muradkarakas/Sodium.git`
   
# Sodium Development (C Language)

* In order to compile all C projects, you must download and install a few more applications listed below.

  * Oracle Database Express Edition (XE) 64Bit 
  * PostgreSQL Datavase 64Bit
  * MySql Database Server 64Bit
  * MS Sql Server 64Bit
  * Redis Server 64Bit

* Add `C:\Sodium\Sodium-Setup` path to the system `PATH` environment variable.

* Add database libray paths to the system `PATH` environment variable.

* Run Visual Studio 2019 Community Edition as administrator. Then find and open `c:\Sodium\Sodium.sln` solution file.

* Compile and link in `Debug` or `Release` profile with 64Bit CPU architecture.

* If you get `library/dll file not found` error message during linkage, please modify project settings according to database library paths.

# Sodium Debug Adaptor Protocol Development (JavaScript)

Sodium has Debug Adaptor Protocol implementation for VS Code.

* Additional to the `Sodium C Projects`, if you want to compile `Sodium Debug Adaptor` for Visual Studio Code, you must also download Visual Studio Code. Find and open `C:\Sodium\DebuggerAdaptor` folder with VS Code application.

