rapidfire
=========

Rapid WP setup via Terminal

Create new account using WHM & Terminal

Open Terminal and enter:

ssh username@myhostname.com [ENTER] and enter password

**** DON'T FORGET to navigate to public_html ****

In Terminal, enter the following three commands: 
wget http://wordpress.org/latest.tar.gz
tar --strip-components=1 -xvf latest.tar.gz
rm latest.tar.gz

Complete WP installation:
mv wp-config-sample.php wp-config.php
nano wp-config-php…

set remote root to theme folder

**** Then, keep site synced on Github ****

On https://github.com create a new repository for the project and initialize repo adding .gitignore WordPress. Edit .gitignore file to add .DS_Store

Copy the address to the project (if the address is not where it seems it should be, go back to account root and back into the repo, e.g.:
￼
Open Coda and set up new Site being sure to set a local folder path. In the Source tab, Clone Get Repository and paste the above into the Repo URL field. Enter password. (If you encounter a connection error due to public key issue, follow the instructions here: https://help.github.com/articles/generating-ssh-keys)

Git for Mac:
Install <a href="https://itunes.apple.com/us/app/xcode/id497799835?mt=12&uo=4" target="itunes_store">Xcode - Apple</a> and then in Preferences >> Downloads install Command Line Tools.

In Coda set:
/Applications/Xcode.app/Contents/Developer/usr/bin/svn
/Applications/Xcode.app/Contents/Developer/usr/bin/git

