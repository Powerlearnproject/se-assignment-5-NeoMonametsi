[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15272872&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   
PREREQUISITES:

1. System requirements:ensure your pc meets the minimum requirements for running vs code and windows 11.
2. Administrator access:you may need administrator privileges on your computer to install software.

STEPS TO DOWNLOAD AND INSTALL VISUAL CODE ON WINDOWS 11:

1.Download vs code installer:-open your browser and go to the visual studio code official website.
                             -click on the download for windows button.
2.Run the installer:-once the download is complete run the installer file.
                    -double click on the installer file to start the installation process.
3.Accept liscense agreement:-you may be prompt to confirm that you want to run the installer,click yes or run to proceed
                            -when the vs code setup wizard opens click next to continue.
4.Select destination location:-choose the destination folder where yiu want to install visual studio code,the default location is usually "c:\program files\microsoft vs code".
5.Select start menu folder:-choose the folder where you want the vs code shortcuts to appear in the start menu or you can leave the default selection.
6.Select additional tasks:-optionally you may be presented with additional tasks like creating a desktop icon or adding vs code to the path environment variable,choose your preferences.
7.Install:-click on the next button to start the inatllation process.
          -the setup will now install vs code on your computer.
8.Finish installation:-click on the finish butyon once installation is complete.
                      -vs code is now installed in your computer

4. First-time Setup:
1. a.Configure user settings:-open vscode and go to file>preferences>settings then customise the settings in the settings.json file,adjust these settings based on your preferences for font size,tab size,word wrappind,formatting on save etc
 b.set up version control (git)if not already installed durind vscode setup:-set your git credentials (git config --global 
                                                                             user.name"your name" and git config --global 
                                                                             user.email "your email")
                                                                             -verify git intergration in vscode by accessing 
                                                                             source cotrol festures in the source control view.
c.customizing keybindings:go to file>preference>keyboard shortcuts.
d.choose theme:file>preference>theme.
e.explore workspace setings:for project-specific settings,create ".vscode/settings.json" in your workplace folder and add 
                           settings specific to that project
f.enable intergrated teriminal by using ctrl+ to toggle the intergrated terminal.customize the shell and its behavior in settings.
g.explore debugging features:set up a debugging configurations "run>add configuration" for different languages and frameworks.
h.use "ctrl+shift+p" to access the command palette for a quick access to various vs code commands and settings.

2. Install essential extentions:bracket pair colorizer,code spell checker,gitlens,live server and eslint/prettier.


5. User Interface Overview:
1.visual code has a user friendly interface designed to enhance productivity and ease of use for developers,the amin components of the vscode user interface are tittle bar,menu bar,activity bar,side bar,editor,status bar,panel,minimap and notifications.These components together make up vscode interface,providing a flexible and customizable environment for coding,debugging and managing projects efficiently.
2.1. Activity bar:the activity bar is positioned vertically on the far left  side of the vscode 
                 window.it houses icons representing different views and functionalities within the editor.
  2. Side bar:the side bar is adjacent to the activity bar and contains various panels that offer additional tools and context 
              relevant to your coding tasks.
  3. Editor group:the editor group is the central area of the vscode interface where you write and edit code.it supports 
                  multiple tabs for editing defferent files simultaneously.
  4. Status bar:the status bar is located at the bottom of the vscode window and provides information and quick access to 
                various setings and tools related to the current file and workspace.

6. Command Palette:
   
1.the command palette in a vscode is a powerfull feature that allows users access various commands,settings and features through a searchable interface.It is particularly useful for executing commands quickly without having to navigate through menus or remember keyboard shortcuts.
2.Accessing the command palette:-keyborad shortcut-press ctrl+shift+p for windows and linux then cmd+shift+p for mac,this will 
                                 open the command pakette at the top center of the vscode window.
                                -menu bar-click on view in the menu bar the select command palette,this will also open the 
                                 command palette.
3.Common tasks that can be performed usig the command palette:opening files and folders,managing editors,searching and 
navigation,version control,debugging,settings and preferences,terminal,task and build,extension-specific tasks and custom commands.

7. Extensions in VS Code:
   
1.Extensions play a crusial role in enhancing and customizing the functionality of vscode,catering to the diverse needs of developers across different programming languages,framewroks and workflows.
2.a.finding extensions:-open vscode.
                      -click on the extensions icon in the activity bar on the side or use ctrl+shift+x/cmd+shift+x.
  b.installing extensions:-in the extensions view search for the extension you want.
                          -click on the extension to view its details.
                          -click instal button to install the extension
  c.mamaging extensions:1.enabling and disabling -in the extension view you can see a list of installed extensions.
                                                 -toggle the switch next to an extension to enable or disable it.
                        2.updating extensions -vscode automatically checks for updates on installed extensions.
                                              -in the extensions view,updates are indicated with an update button next to to 
                                               extensions that have available extensions.
                                              -click update to install the latest update.
                        3.uninstalling extension: -in the extension view,right click on an extension you want to uninstall and 
                                                   click uninstall.
                                                  -alternatively you can go to the extension's details page and click on 
                                                   uninstall.
                        4.settings and cofiguration:some extensions provide configuration options that can be accessed through 
                                                    the settings "ctrl+,/cmd+," under the extensions category.
                        5.managing extensions globally or locally: -extensions can be installed globally for all vacode 
                                                                    instances or locally per workpspace.
                                                                   -global extensions are managed through the extensions view 
                                                                    while local extensions are mananged within the workapace's 
                                                                    ".vscode/extensions"folder.
3.examples of essential extensions for web development:ESLint,Prettier-Code formatter,Live Server,Debugger for Chrome,Auto Rename Tag,Bracket Pair Colorizer,Path Intellisense,CSS Peek,HTML CSS Support and GitLens.

8. Integrated Terminal:
   
1.opening intergrated terminal-using the menu:click view in the menu bar at the top of vscode,select termainal from the drpdown 
                               menu then choose the new terminal to open s new intergrated terminal panel at the bottom of the 
                               ditor.
                               -using keyboard shortcuts:use shortcut ctrl+ on windows/linux and cmd+ on macos.This will toggle 
                               the intergrated terminal panel(openor close if already open).
2.using the intergrated terminal:1.navigating directories:use standard command-line navigation commands like cd to navigate 
                                through directories e.g "cd my-project" to change directory to my-project.
                                2.running commands and scripts:execute commands directly in the terminal such as "npm install" 
                                to install dependencies or "git commit -m "commit message"" to commit message to git.run 
                                scripts defined in your "package.json"or other script files.
                                3.intergrating with shells:by default vscode uses your systems's default shell like bash on 
                                macos/linux or poweshell on windows but you can cahne the default shell or configure specific 
                                shells in vscode settings(settings.json).
                                4.terminal settings and customization:you can customiza various aspects of the intergrated 
                                terminalsuch as font size,colors,shell configuration and more through vscode settings 
                                (ctrl+,/cmd+,).
                                5.split terminals:you can split the terminal into multiple panes by clicking on the spli icon 
                                '+' button on the terminal panel or by right-clicking and selecting split terminal.This allows 
                                you to work multiple terminals simultaneously.
                                6.terminal navigation shortcuts:use ctrl+ shortcut to toggle the terminal,ctrl+shift+ to create 
                                a new terminal and ctrl+ flowwed by ctrl+2 to split the terminal vertically.

9. File and Folder Management:
CREATING AND OPENING NEW FILES AND FOLDERS:
creating a new file:1.click on the explorer icon in the activity bar on the side.
                    2.right-click on the folder where you want to create a new file.
                    3.select new flie from the context menu,enter desired filenamethe press enter to create file.
creating a new folder:1.right-click on the parent folder in the explorer view.
                      2.select new folder from the context menu,enter the folder name snd press enter to create the folder.
opening files and folders:1.to open a file simply double-click on it in the explorer view or right-click and select open.
                          2.to open folder either double-click on it in the explorer view or use( file>open folder) from the 
                          menu bar and navigate desired folder.
   
MANAGING FILES AND FOLDERS:
renaming files and folders:1.right-click on the file or folder in the explorer view.
                           2.select rename from the context menu.
                           3.enter the name and press enter to apply change.
moving files and folders:1.drag and drop files or folders within the explorer view to move the to a different location.
                         2.alternatively right-click on the item,select cut,navigate to target location,right-click and select 
                         paste.
deleting files and folders:1.right-click on the file or folder on the explorer view.
                           2.slect delete on the context menu.
                           3.confirm deletation in the dialod box that appears.
searching for files:1.use the serach box at the top of the explorer view
                    2.start typing the file name or part of it to search for files within the cuurent workspace.
using file navigation shortcuts:use ctrl+Tab to cycle through open files,ctrl+P/cmd+P followed by the file name to quickly open 
                               files using quick open and ctrl+shift+E/cmd+shift+E to toggle the explorer view.

NAVIGATING BETWEEN DIFFERENT FILES AND DIRECTORIES EFFICIENTLY:

1.USING THE EXPLORER VIEW:
opening the explorer view:click on the explorer icon in the activity bar on the side or use ctrl+shift+E/cmd+shift+E
navigating fies and folders:1.expand and collapse-click on folder icons to expand or collapse directories.
                            2.double-click-double-click on a file to open it.
                            3.right-click options-right click on files or folders for context menu options like 
                            opening,renaming,deleting etc.
2.USING KEYBOARD SHORTCUTS:
quick open:1.press ctrl+p (windows or linux) cmd+p (macos) to quick open.
           2.type the name of the file you want to open and select from the list.
           3.use @ to navigate to symbols within file(function,classes etc).
switch between tabs:1.use ctrl+tab(windows/linux)/cmd+tab(macos) to cycle through open files.
                    2.press ctrl+shift+tab(windows/linux)or cmd+shoft+tab(macos) to cycle backward through open files.
3.USING FILE NAVIGATION SHORTCUTS:
go to file:1.press ctrl+p(windows/linux)cmd+p(macos) to open quick open.
           2.type @ follwed by the file name to quickly navigate to a file e.g @myflie.js to navigate directly to myfile.js.
go to symbol file:1.press ctrl+shift+0(windows/linux)cmd+shift+0(macos) to open go to symbol view.
                  2.type to search for a symbol within the currently open file.
4.USING WORKSPACE SYMBOLS:
go to symbol in workspace:1.press ctrl+t(windows/linux)cmd+t(macos) to search symbols across the entire workspace.
                          2.type to search foe asymbol and navigate directly to iys definition.
5.USING THE COMMAND PALETTE:
navigate to the file symbol:1.press ctrl+shift+p(windows/linux)cmd+shift+p(macos) to open command palette.
                            2.type go to file or go to symbol to access commands for navigating files and symbols efficiently.
6.USING EXTENTIONS:
project management extensions:install extensions like project manager or bookmarks to manage and quickly navigate between 
                              different projects and files within vscode.

10. Settings and Preferences:
   - Where can users find and customize settings in VS Code?
     
     settings menu:open vscode and click on the gear icon located in the bottom left corner of the activity bar.
     command palette:use the keyboard shortcut ctrl+shift+p(windows/linux)cmd+shift+p(mac to open the command palette.type 
                    "preferences:open settings(json/ui)" to open settings in the json format or the user interface respectively.
     file menu:on windows or linux click on file>preferences>setings,on macos click on code>preferences>settings
     once in the settings view you can customize various aspects of vscode:1.user settings apply globally to all vscode 
                                                                           instances.
                                                                           2.workplace settings are specifice to the current 
                                                                           opened workspace and override settings.
              
   - Provide examples of how to change the theme, font size, and keybindings.
     
     changing theme:1.open vscode,click on the gear icon in the bottom left corner to open settings view.
                    2.in the search bar at the top of the settings view tyep "color theme",click on color theme uder wrokbench.
                    3.choose a theme from a dropdown list o apply it instantly.
     changing font size:1.open settings view using gear the icon,in search bar tyep "font size".
                        2.find editor:font size and adjust the value of your desired size.
     changing keybindings:1.open the command palete and type "preferences",open the keybingings file in json format.
                          2.here you add custom keybindings or modify existing ones.

11. Debugging in VS Code:
 - Outline the steps to set up and start debugging a simple program in VS Code.

     create a simple program:create a simple progrsm in your preferred programming alnguage.e.g basic'hello,wprld"progam in 
                            python "hello.py",save the file directory where you can easily acces it.
     open the project in vscode:open vscode and navigate where hello.py is located,use file>open folder to open the folder 
                               containing your program.
     configure debugging:1.click on the debugging icon in the activity bar on the side of the vscode.
                         2.if you dont hhave a lauch.json file already,vscode will prompt you to create one,click on create a 
                         lauch.json and select the environment appropriate for your program.
                         3.if you already have a lauch.json file you can edit it directly,ensure it contains the neccessary 
                         configuration for your programming language.
     start debugging:1.set breakpoints in your code by clicking in the left-hand gutter next to the line numbers where you want 
                     to pause execution.
                     2.press f5 or click on the green play button next to configuration dropdown in the debug view to start 
                     debugging.
                     3.vscode will start your program in debug mode.it will pause at the breakpoints you have set allowing you 
                     to inspect variables,step through code and analyze program flow.
                     debugging controls:f10 to execute the current line and move to the next one,f11 to dive into a function 
                     call and debug inside it,shit+f11 to finish debugging the current function and return to the calling 
                     function,f5 to resume execution until it's next breakpoint or end of the program and shift+f5 to stop 
                     debugging.
     refiew output:the debug console in vscode displays output from your program and allows you to interact with it during 
                  debugging.
     
 -  What are some key debugging features available in VS Code?

 breakpoints,variable inspection,watch expressions,call stack,debug console,run and debug configrations and intergated terminal.

12. Using Source Control:
- How can users integrate Git with VS Code for version control?
1.install git
2.install vscode
3.open project folder on vscode
4.initialize git repository
5.set up git in vscode
6.use git features in vscode
7.configure git settings
8.git extensions
9.resolve conflicts and mange branches
  
- Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
initialize a git repository:1.open vscode-lauch vscode and open the folder or workspace your project rsides.
                            2.open terminal-go to terminal>new terminal.
                            3.initialize git-in the terminal navigate to your project directory and run this command'git init'.
make commit:1.stage files-use source control view in vscode to review changes.
                         -untracked files will appear under changes,click + button next to file to stage it for commit.
            2.commit changes-at the top of the source control view there is a text box labeled message,enter your commit 
                             message describing the changes made.
                            -press ctrl+enter(windows/linux)cmd+enter(macos)to commit changes.
push changes to github:1.create a github repository if you haven't created one on github.
                       go to github log in,click + in the top corner and select new repository,follow instructions and create 
                       one and optionally adding a readme file.
                       2.set remote origin:in the terminal,add url of your github repository as the remote origin,replace 
                       <remote_repository_url> with your github repository(you cna find this url on your github under clone or 
                       download).
                       3.push your commited changes to github (git push -u origin main),origin refers to the remote repository 
                       on github and amin is the branch name youre pushing to.
  
  
 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

