cssFoldedPosterEffect

seeing of twitter post of https://twitter.com/lynnandtonic and try it. Original source code https://codepen.io/lynnandtonic/pen/PoZpjOr

If you going to try original code. You will notice some errors on css. Cause you need to use stylus to convert it.
I will tell you step by step how you can install it and use it.

1) fist thing first you need to install node.js
For Ubuntu you can directly download with 'apt'
"sudo apt-get install nodejs" 
then run intall globaly with 'npm'
"sudo npm install -g stylus"

For MacOS first install 'brew' ( https://brew.sh )
" /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)" "
then install 'node.js'
" brew install node "
and install 'stylus' globaly
" npm install -g stylus " 

For Windows go to Node.js website ( https://nodejs.org/en/ ) then download and install
after that install 'Stylus' with npm
" npm install stylus -g "

2)After the installation of Stylus 
You can use like this command.
" stylus -c website/style.css "
it will generate .css file so you can use your website

If you ask 'Why i used that?'
If you notice original code has no  curl braces or semicolon. Normally this is wrong and website won't use this .css. But after the we use stylus all this appared. Stylus help us to get out the syntax error from this guys. In big projects it's very big deal.