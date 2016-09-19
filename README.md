Sample role for ansible meetup
=========

Requirements
------------

* ruby
* bundler
* test-kitchen (gem)
* kitchen-ansible (gem)
* kitchen-docker (gem)
* kitchen-sync (gem) - Optional for OSX

Setup
--------------

checkout repo into your roles parent  directory. 
```
#-bash:$
cd <my-path-to-the-roles-parent-dir>
#-bash:$
ls
.
..
roles
other-dir
#-bash:$
git clone git@github.com:sirkjohannsen/meetuprole.git 
```
Install gems:
```
bundle
```

Usage
------------

```
kitchen test
```
