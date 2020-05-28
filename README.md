<!-- ****************************************************************************************************************** -->


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
* [\C++](#cpp)
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

| Syntax                                 | Description                            |
|----------------------------------------|----------------------------------------|
| `git init`                             | Initialize a git repository.           |
| `git clone <url>`                      | Clone a repository.                    |
| `git commit -m "some-commit-message"`  | Commit your changes with a message.    |
| `git pull`                             | Pull from a repo.                      |
| `git push "repo-name" "branch-name"`   | Push your changes to a repo.           |
| `git remote show origin`               | Shows the url of the cloned repository.|

<div align ="right"> <b><a href="#table-of-contents">⬆️ Back To Top</a></b></div>
    
<!-- ****************************************************************************************************************** -->




<!-- ****************************************************************************************************************** -->

<a name="html"></a>

# HTML

| Command                                | Description                            |
|----------------------------------------|----------------------------------------|
| `<!-- This is an HTML Comment -->`     | Comment syntax for html.               |
| `<img src="image/path/here">`          | Image syntax for html.                 |
| `<a name="link name">"anchor text</a>` | Creates a link with specified anchor text. |
| `<p>Paragraph 1</p>`                   | Paragraph syntax for html.             |
|                                    **HEADERS**                                  |
| `<h1>header 1</h1>`                    | Header Level 1                         |
| `<h2>header 2</h2>`                    | Header Level 1                         |
| `<h3>header 3</h3>`                    | Header Level 1                         |
| `<h4>header 4</h4>`                    | Header Level 1                         |
| `<h5>header 5</h5>`                    | Header Level 1                         |
| `<h6>header 6</h6>`                    | Header Level 1                         |
|                                    **LISTS**                                    |
| `<li>List Item</li>`                   | List item                              |
| `<ol>Ordered List</ol>`                | Ordered list                           |
| `<ul>Unordered List</ul>`              | Unordered list                         |
|                                 **SEMANTIC TAGS**                               |
| `<article>Article 1</article>`         | Article section syntax for html.       |
| `<footer>Footer 1</footer>`            | Footer section syntax for html.        |
| `<header>Header 1</header>`            | Header section syntax for html.        |    
| `<main>Main 1</main>`                  | Main section syntax for html.          |




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
| `javac "filename.java"`                | Compiles java file, creates class file.|
| `java "class-name"`                    | Runs program with the given class name.|

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
|                                    **HEADERS**                                  |
| `# header1`                            | Header Level 1                         |
| `## header2`                           | Header Level 2                         |
| `### header3`                          | Header Level 3                         |
| `#### header4`                         | Header Level 4                         |
| `##### header5`                        | Header Level 5                         |
| `###### header6`                       | Header Level 6                         |
|                                    **Lines**                                    |
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

| Node Version Manager (NVM) Command     | Description                            |
|----------------------------------------|----------------------------------------|
| `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash` | Installs NVM. |
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
| `cd` <br/> `cd ~` <br/> `cd ~/`        | Brings you to home directory.          |
| `cd "path/to/directory/"`              | Brings you to a specified directory.   |
| `chmod 777 "directory/path"`           | Grants RWX permissions to all users.   |
| `chmod 755 "directory/path"`           | Grants R-X permissions to group and others.|
| `clear`                                | Clears your terminal.                  |
| `echo "your string"`                   | Repeat the input.                      |
| `ls` <br/> `ls "path/to/directory/"`   | List current directory.                |
| `ls -a`                                | Show all files including hidden ones.  |
| `ls -l`                                | Show all files and their permissions.  |
| `mkdir "path/to/new/directory"`        | Make a directory.                      |
| `mv "filename" "path/to/new/location"` | Move a file.                           |
| `mv "filename" "newfilename"`          | Rename a file.                         |
| `open "filename"`                      | Open a file.                           |
| `touch "filename.filetype"`            | Make a file.                           |

<br/>
<br/>
<br/>

| Homebrew Command                       | Description                            |
|----------------------------------------|----------------------------------------|
| `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` | Installs homebrew.                                                                         |
|                                   **PACKAGES**                                  |
| `brew install nvm`                     | Homebrew installs nvm package.         |
| `brew install pyenv`                   | Homebrew installs pyenv package.       |
| `brew install sqlite`                  | Homebrew installs sqlite package.      |
| `brew install tree `                   | Homebrew installs tree package.        |
| `brew install zlib`                    | Homebrew installs zlib package.        |

<br/>
<br/>
<br/>

| Python Command                         | Description                            |
|----------------------------------------|----------------------------------------|
| `python3 -m venv "name of venv"`       | Create virtual environment.            |
|                                     **PIP**                                     |
| `pip3 list`                            | List all pip3 packages.                |


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



