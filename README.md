# Source code for James' website
See it live at _________

The page leverages:
 - jekyll to put it all together
 - bootstrap 5 to make it look pretty 
 - GitHub Pages (so static hosting) to make it available to the world

## For local testing and development use the vagrant setup
I have Vagrant set up so it can start a development VM for testing
### Make sure you install
 - Git
 - Vagrant
 - VirtualBox
  
### INITIAL Setup (you only have to do this once)
```
$ vagrant up
$ vagrant ssh
# you have to reboot once due to something that gets installed
$ sudo reboot now # this will kick you out, that's okay, just wait a moment or two
$ vagrant ssh
$ cd /vagrant
$ gem install bundler
$ bundle install
```

### Running the development server 
```
$ vagrant up
$ vagrant ssh
$ cd /vagrant
$ bundle exec jekyll serve --host 0.0.0.0 --port 4100 --force-polling
```

You'll now be able to view the page from your host OS via <http://127.0.0.1:4100>

## Making images appropriate for this site
Images are in subfolders of 'images'
convert them via the guest vm and the helper script go to the folder with the base image and type
```$ ../makewebready.sh <filenamenoextension> ```
I.e. take the extension off the filename

