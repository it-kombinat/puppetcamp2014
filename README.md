puppetcamp2014
==============

puppet, git, r10k and jenkins - CI - DEMO

@https://github.com/tosmi/puppetcamp2014

usage
=====
```git clone --recursive https://github.com/it-kombinat/puppetcamp2014.git```

## To start vagrant in the cloned folder
* change into the cloned repository folder and type ```vagrant up --provision```

## Login into the jenkins
open ```http://localhost:8080``` in your favourite browser

## Further playing and testing - Load GITOLITE Key
* ```eval "$(ssh-agent -s)"```
* ```ssh-add /vagrant/ssh/gitolite```
* ```cd /home/vagrant/git/puppet```

###Change site.pp and ssee what happens
* ```vi site/samplemodule/manifests/init.pp```
* ```git commit```
* ```git push```

#############################

