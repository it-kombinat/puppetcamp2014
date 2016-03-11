puppetcamp2014
==============

Puppetcamp Duesseldorf 2014 Talk about puppet, git, r10k and jenkins.

usage
=====
```git clone --recursive https://github.com/tosmi/puppetcamp2014.git```

## To start vagrant in the cloned folder
* change into the cloned repository folder and type ```vagrant up --provision```

## Login into the jenkins
open ```http://localhost:8080``` in your favourite browser

## Further playing and testing - Load GITOLITE Key
```eval "$(ssh-agent -s)"```
```chmod 0600 /vagrant/ssh/gitolite```
```ssh-add /vagrant/ssh/gitolite```

```cd /home/vagrant/git/puppet```

###Change site.pp and ssee what happens
```vi site/samplemodule/manifests/init.pp```
```git commit```
```git push```

#############################

