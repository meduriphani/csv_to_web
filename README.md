Create folders named such as backend-server and moveit-automation
open the command prompt and navigate to the newly created directories in the 1st step
This step is not required if the directories have already package.json (To create new package.json issue - npm init -y)
To install the node packages run the command from corresponding directory  - npm install
Check where the ng.cmd or ng.sh is available and set the path.  [command is - set PATH=%PATH%;C:\Users\username\IdeaProjects\express\node_modules\.bin;]
ng serve --proxy-config proxy.conf.json

