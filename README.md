##Getting Started

### 1. Installation
*  Download and run the [RailsInstaller for Windows](http://rubyforge.org/frs/download.php/75894/railsinstaller-2.1.0.exe)

*  For all the shell commands below, do **not** use the standard command prompt. Instead, use the newly created shortcut "Command Prompt with Ruby and Rails" 

### 2. Checking Ruby and Console
*  Check if the ruby version is correct (1.9.3p125)

  ```bash
  $ ruby -v
  ```

*  Open the ruby console and try out some sample code

  ```bash
  $ irb
  irb(main):001:0) puts "hello"
  hello
  => nil
  irb(main):002:0)
  ```

### 3. Update gems
*  _Optional_ : To make gem installs faster, create/update the file "C:\ProgramData\gemrc" with the following line (which disabled download of documentation)
  ```bash
  gem: --no-ri --no-rdoc
  ```

*  Update the bundler and rails gems
  ```bash
  $ gem update bundler rails
  ```

### 4. Create new Rails App 
*  Create a new rails app
  ```bash
  $ rails new trial
  ```

*  Switch to the directory and run the rails server
  ```bash
  $ cd trial 
  $ ruby script/rails server
  ```

*  Visit http://localhost:3000 to check if the application is running

### 5. [Optional] Sublime Text 2 Editor
*  Install [Sublime Text 2](http://c758482.r82.cf2.rackcdn.com/Sublime%20Text%202.0.1%20x64%20Setup.exe) 


