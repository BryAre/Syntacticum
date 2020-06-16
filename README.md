<!-- ****************************************************************************************************************** -->

![](https://img.shields.io/github/contributors/bryare/syntacticum?color=light-green)
[![HitCount](http://hits.dwyl.com/BryAre/Syntacticum.svg)](http://hits.dwyl.com/BryAre/Syntacticum)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)

___

![BryAre](https://img.shields.io/badge/BryAre-made%20with%20%F0%9F%92%96-brightgreen)

# **Project Syntacticum** #


### Overview

Project Syntacticum is a compendium of various technologies and programming languages that documents their respective 
syntax. The purpose of this compendium is not to give examples of code using syntax, but is to be used only to reference 
syntax.


### Syntax

- New section:          **`# NEW SECTION / acronym expansion (".filetype") #`**
- New item:               **`- "NEW ITEM" `**
- Highlight Syntax:   **` ```HIGHLIGHT CODE``` `**
- New Table:           
`| Heading 1 | Heading 2 | Heading 3 |` <br/>                               
`|-----------|-----------|-----------|` <br/>                                
`|  item 1   |   item 2  |   item 3  |`


<a name="table-of-contents"></a>

### Table of Contents

* [C](#c)
* [C++](#cpp)
* [Git](#git)
* [HTML](#html)
* [Java](#java)
* [Markdown](#markdown)
* [NodeJS](#nodejs)
* [Terminal](#terminal)


### Contributing Guidelines
* Add only one definition in one pull request.
* Pull request title format includes: [Syntax Name] -> [Section]
    * Example: [For Loop] -> [Java]
* Provide a reference for the syntax.
    * Example: Link: https://www.w3schools.com/java/java_for_loop.asp


<!-- ****************************************************************************************************************** -->





<!-- ****************************************************************************************************************** -->

<a name="c"></a>

# C #

<br/>
<br/>
<br/>

| Command                                | Description                            |
|----------------------------------------|----------------------------------------|
| `gcc "filename.c"`                     | Compiles file and produces executable. |

<br/>
<br/>
<br/>

<div align ="right"> <b><a href="#table-of-contents">⬆️ Back To Top</a></b></div>

<!-- ****************************************************************************************************************** -->





<!-- ****************************************************************************************************************** -->

<a name="cpp"></a>

# C++ #

<br/>
<br/>
<br/>

| Command                                | Description                            |
|----------------------------------------|----------------------------------------|
| `g++ "filename.c" -o "executable-name"`| Compiles file and produces executable. |

<br/>
<br/>
<br/>

<div align ="right"> <b><a href="#table-of-contents">⬆️ Back To Top</a></b></div>

<!-- ****************************************************************************************************************** -->





<!-- ****************************************************************************************************************** -->

<a name="git"></a>

# Git

<br/>
<br/>
<br/>

| Syntax                                 | Description                            |
|----------------------------------------|----------------------------------------|
|                      <br/> **INITIALIZE REPOSITORY** <br/> <br>                 |      
| `git clone "url"`                      | Clone an already created repository.   |
| `git init`                             | Initialize a git repository.           |
|                           <br/> **LOCAL CHANGES** <br/> <br>                    |            
| `git add .`                            | Adds all changes to the commit.        |
| `git add "file"`                       | Add specified file's changes to commit.|
| `git commit -m "some-commit-message"`  | Commit staged changes with a message.  |
| `git status -s`                        | Show status of files in staging area.  |
|                             <br/> **HISTORY** <br/> <br>                        |            
| `git blame "filename"`                 | Shows changes made by a person.        |
| `git log`                              | Shows all commits.                     |
| `git log --online`                     | Shows all commits in line format.      |
| `git diff`                             | Shows diff between work and stage.     |
|                             <br/> **UPDATES** <br/> <br>                        |            
| `git pull`                             | Fetches and merges into local branch.  |
| `git push origin "branch-name"`        | Push your changes to a repo.           |
| `git remote show origin`               | Shows the url of the cloned repository.|
| `git rm "filename"`                    | Remove a file from a repository.       |
| `git rm -f "filename"`                 | Force delete a file.                   |
| `git rm -r "foldername"`               | Recursively delete a directory.        |
|                             <br/> **BRANCHES** <br/> <br>                       |            
| `git branch`                           | Outputs current branch.                |
| `git branch -av`                       | Outputs all branches.                  |
| `git branch -d "branch-name"`          | Delete selected branch.                |
|                               <br/> **USER** <br/> <br>                         |            
| `git config --global user.email "mail"`| Set your email address in git.       

<br/>
<br/>
<br/>

<div align ="right"> <b><a href="#table-of-contents">⬆️ Back To Top</a></b></div>
    
<!-- ****************************************************************************************************************** -->




<!-- ****************************************************************************************************************** -->

<a name="html"></a>

# HTML #

<br/>
<br/>
<br/>

| Command                                | Description                            |
|----------------------------------------|----------------------------------------|
| `<!-- This is an HTML Comment -->`     | Comment syntax for html.               |
| `<img src="image/path/here">`          | Image syntax for html.                 |
| `<a name="link name">anchor text</a>`  | Creates a link.                        |
| `<p>Paragraph 1</p>`                   | Paragraph syntax for html.             |
|                             <br/> **HEADERS** <br/> <br/>                       |
| `<h1>header 1</h1>`                    | Header Level 1                         |
| `<h2>header 2</h2>`                    | Header Level 1                         |
| `<h3>header 3</h3>`                    | Header Level 1                         |
| `<h4>header 4</h4>`                    | Header Level 1                         |
| `<h5>header 5</h5>`                    | Header Level 1                         |
| `<h6>header 6</h6>`                    | Header Level 1                         |
|                              <br/> **LISTS** <br/> <br/>                        |
| `<li>List Item</li>`                   | List item                              |
| `<ol>Ordered List</ol>`                | Ordered list                           |
| `<ul>Unordered List</ul>`              | Unordered list                         |
|                            <br/> **SEMANTIC TAGS** <br/> <br/>                  |
| `<article>Article 1</article>`         | Article section syntax for html.       |
| `<footer>Footer 1</footer>`            | Footer section syntax for html.        |
| `<header>Header 1</header>`            | Header section syntax for html.        |    
| `<main>Main 1</main>`                  | Main section syntax for html.          |

<br/>
<br/>
<br/>

<div align ="right"> <b><a href="#table-of-contents">⬆️ Back To Top</a></b></div>
    
<!-- ****************************************************************************************************************** -->





<!-- ****************************************************************************************************************** -->

<a name="java"></a>

# Java #

<br/>
<br/>
<br/>

| Command                                | Description                            |
|----------------------------------------|----------------------------------------|
| `java "class-name"`                    | Runs program with the given class name.|
| `javac "filename.java"`                | Compiles java file, creates class file.|

<br/>
<br/>
<br/>

<div align ="right"> <b><a href="#table-of-contents">⬆️ Back To Top</a></b></div>

<!-- ****************************************************************************************************************** -->




<!-- ****************************************************************************************************************** -->

<a name="javascript"></a>

# JavaScript #

<br/>
<br/>
<br/>

| Command                                | Description                            |
|----------------------------------------|----------------------------------------|
| `let var = datatype`                   | Creates a variable available in scrope declared only. |
| `const var = datatype`                 | Creates a variable that cannot be modified. |
| `var var = datatype`                   | Creates a variable that can be overwritten and used anywhere. |
| `let x = ['a', 'b','c']`               | Makes an array in the given scope.     |

<br/>
<br/>
<br/>

<div align ="right"> <b><a href="#table-of-contents">⬆️ Back To Top</a></b></div>

<!-- ****************************************************************************************************************** -->



<!-- ****************************************************************************************************************** -->

<a name="markdown"></a>

# Markdown #

<br/>
<br/>
<br/>

| Command                                | Description                            |
|----------------------------------------|----------------------------------------|
|                             <br/> **HEADERS** <br/> <br/>                       |
| `# header1`                            | Header Level 1                         |
| `## header2`                           | Header Level 2                         |
| `### header3`                          | Header Level 3                         |
| `#### header4`                         | Header Level 4                         |
| `##### header5`                        | Header Level 5                         |
| `###### header6`                       | Header Level 6                         |
|                              <br/> **LINES** <br/> <br/>                        |
| `***` <br/> `---` <br/> `___`          | Makes a horizontal line.               |

<br/>
<br/>
<br/>

<div align ="right"> <b><a href="#table-of-contents">⬆️ Back To Top</a></b></div>

<!-- | `***`  <br/> `---` <br/> `___`         | Makes a horizontal line.               | -->
<!-- 
| `# header1` <br/> `## header2` <br/> `### header3` <br/> `#### header4` <br/> `##### header5` <br/> `###### header6` | Header Level 1 <br/> Header Level 2 <br/> Header Level 3 <br/> Header Level 4 <br/> Header Level 5 <br/> Header Level 6     | -->

<!-- ****************************************************************************************************************** -->





<!-- ****************************************************************************************************************** -->

<a name="nodejs"></a>

# NodeJS #

<br/>
<br/>
<br/>

| Node Package Manager (NPM) Command     | Description                            |
|----------------------------------------|----------------------------------------|
| `npx create-react-app "app-name"`      | Creates a react app with given name.   |
| `npm init react-app "app-name"`        | Creates a react app with given name.   |
| `npm start` <br/> `npm run start`      | Runs the app in development mode.      |
| `npm run deploy`                       | Create build directory for production. |
|                             <br/> **PACKAGES** <br/> <br/>                      |
| `npm install @iconify/react`           | NPM installs iconify/react package.    |
| `npm install @iconify/icons-logos`     | NPM installs iconify/icons-logos pkg.  |
| `npm install bootstrap`                | NPM installs bootstrap package.        |
| `npm install browser-router`           | NPM installs browser router package.   |
| `npm install electron`                 | NPM installs electron package.         |
| `npm install node-sass`                | NPM installs node-sass package.        |
| `npm install react-bootstrap`          | NPM installs react-bootstrap package.  |
| `npm install react-anime`              | NPM installs anime package.            |
| `npm install webfontloader`            | NPM installs webfont loader package.   |
| `npm install gh-pages`                 | NPM installs github pages package.     |


<br/>
<br/>
<br/>

| Node Version Manager (NVM) Command     | Description                            |
|----------------------------------------|----------------------------------------|
| `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh `\|` bash` | Installs NVM. |
| `nvm install node`                     | Installs latest nodeJS version.        |
| `nvm ls`                               | Shows all installed node versions.     |
| `nvm ls-remote`                        | Shows all available node lts versions. |
| `nvm run node`                         | Runs the CLI for nodeJS.               |
| `nvm use node`                         | Sets node version to latest installed. |

<br/>
<br/>
<br/>

<div align ="right"> <b><a href="#table-of-contents">⬆️ Back To Top</a></b></div>

<!-- ****************************************************************************************************************** -->





<!-- ****************************************************************************************************************** -->

<a name="terminal"></a>

# Terminal #

<br/>
<br/>
<br/>

| Command                                | Description                            |
|----------------------------------------|----------------------------------------|
|                             <br/> **GENERAL** <br/> <br/>                       |
| `clear`                                | Clears your terminal.                  |
| `curl -O "file-url"`                   | Download file from a given url         |
| `kill "pid"`                           | Kills the process with given id.       |
| `top`                                  | Shows all running processes.           |
| `k1 | k2`                              | Enters k1's output into k2's input     |
| `command&`                             | Background process.                    |
|                           <br/> **DIRECTORIES** <br/> <br/>                     |
| `cd` <br/> `cd ~` <br/> `cd ~/`        | Brings you to home directory.          |
| `cd ..`                                | Brings you to parent directory.        |
| `cd "path/to/directory/"`              | Brings you to a specified directory.   |
| `ls`                                   | List current directory.                |
| `ls -a`                                | Show all files including hidden ones.  |
| `ls -l`                                | Show all files and their permissions.  |
| `ls "path/to/directory/"`              | List path directory.                   |
| `mkdir "path/to/new/directory"`        | Make a directory.                      |
|                              <br/> **FILES** <br/> <br/>                        |
| `cat "filename"`                       | Show output of the file.               |
| `cat "filename | wc"`                  | Shows line, words, and characters.     |
| `echo "your string" >> "filename"`     | Input string into the file.            |
| `grep keyword filename`                | Outputs occurences of keyword in file. |
| `grep -n keyword filename`             | Outputs occurences in file with line #.|
| `mv "filename" "path/to/new/location"` | Move a file.                           |
| `mv "filename" "newfilename"`          | Rename a file.                         |
| `open "filename"`                      | Open a file.                           |
| `rm "filename"`                        | Delete a file.                         |
| `rm -f "filename"`                     | Force delete a file.                   |
| `rm -r "directory"`                    | Recursively delete a directory.        |
| `touch "filename.filetype"`            | Make a file.                           |
|                           <br/> **PERMISSIONS** <br/> <br/>                     |
| `chmod 777 "directory/path"`           | Changes file permissions to 777.       |
| `chmod 755 "directory/path"`           | Changes file permissions to 755.       |

<br/>
<br/>
<br/>

| Homebrew Command                       | Description                            |
|----------------------------------------|----------------------------------------|
| `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` | Installs homebrew.                                                                         |
|                             <br/> **PACKAGES** <br/> <br/>                      |
| `brew install nvm`                     | Homebrew installs nvm package.         |
| `brew install pyenv`                   | Homebrew installs pyenv package.       |
| `brew install rbenv`                   | Homebrew installs rbenv package.       |
| `brew install sqlite`                  | Homebrew installs sqlite package.      |
| `brew install tree `                   | Homebrew installs tree package.        |
| `brew install zlib`                    | Homebrew installs zlib package.        |

<br/>
<br/>
<br/>

| Python Command                         | Description                            |
|----------------------------------------|----------------------------------------|
| `python3 -m venv "name of venv"`       | Create virtual environment.            |
| `python3 -v`                           | Displays the current version of python.|
|                               <br/> **PIP** <br/> <br/>                         |
| `pip3 list`                            | List all pip3 packages.                |

| Ruby Command                           | Description                            |
|----------------------------------------|----------------------------------------|
| `ruby -v`                              | Displays the current version of ruby.  |
|                               <br/> **RBENV** <br/> <br/>                       |
| `rbenv init`                           | Initialize rbenv.                      |
| `rbenv install 2.x.x`                  | Installs a given version of ruby.      |
| `rbenv global 2.x.x`                   | Sets shell default ruby version.       |



<br/>
<br/>
<br/>

| Xcode Command                          | Description                            | 
|----------------------------------------|----------------------------------------|
| `xcode-select --install`               | Installs Xcode CLI tools on macOS.     |

<br/>
<br/>
<br/>

<div align ="right"> <b><a href="#table-of-contents">⬆️ Back To Top</a></b></div>
    
<!-- ****************************************************************************************************************** -->



