# installST

```
#!/bin/bash -x
# This script installs sublime text 3 
# Change permissions first with: chmod 0755 installST.sh
# Then run with: ./installST.sh

sudo add-apt-repository ppa:webupd8team/sublime-text-2
sudo apt-get update
sudo apt-get --purge remove sublime-text*
sudo apt-get install sublime-text
subl .

```
