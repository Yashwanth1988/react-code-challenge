# react-code-challenge

To run.
-------------

Due to security issues gmail is blocking the *.js files to send.
so to overcome that I have to rename all .js to .txt
 
please run this command to convert *.txt to *.js under the directory extracted "/react-challenge-completed"
	> FOR /R %x IN (*.txt) DO ren "%x" *.js

Then please run - "npm install" command to get the node modules installed.

Then build app by "npm run build" - (changes are being watched with webpack --watch).

And then start app by "npm run start" - (will trigger the server at port 3000, this is an express server)

hit : localhost:3000
