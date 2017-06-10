<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="http://github.com/iJackUA/awesome-vagrant">iJackUA/awesome-vagrant</a> with ranks
</p>
---
# Awesome Vagrant
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](https://github.com/sindresorhus/awesome) [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/iJackUA/awesome-vagrant?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) [![Build Status](https://api.travis-ci.org/iJackUA/awesome-vagrant.svg?branch=master)](https://travis-ci.org/iJackUA/awesome-vagrant)

A curated list of awesome Vagrant resources, plugins, tutorials and other nice things.


## Official resources

* [Vagrant site](https://www.vagrantup.com/) - installation instruction, official manuals and docs.
* [GitHub repo ★14684](https://github.com/mitchellh/vagrant) - source code, issues discussion and collaboration.


## Boxes

*Where to find OS boxes ?*

* [Vagrantbox.es](http://www.vagrantbox.es/) - the biggest list of all available boxes, maintained by community via GitHub pull requests.
* [Vagrant Cloud](https://atlas.hashicorp.com/boxes/search) - config share, boxes distribution and discovery (also premium features of private collaboration and sharing).
* [Cloud Images Ubuntu.com](https://cloud-images.ubuntu.com/vagrant/) - "clean" official Ubuntu cloud images.
* [Baseboxes from Opscode ★2412](https://github.com/chef/bento#current-baseboxes) - CentOS, Fedora, Debian, FreeBSD, Ubuntu.
* [Puppet Labs Vagrant Boxes](http://puppet-vagrant-boxes.puppetlabs.com/) - these boxes are provided to be used by various Puppet projects.


## Provisioning

* [All available build in provisioning providers](https://www.vagrantup.com/docs/provisioning/index.html) - official doc.
* [Vaprobash](http://fideloper.github.io/Vaprobash/index.html) - Vagrant Provisioning Bash Scripts.


## Notable plugins

*You can install these modules by this command `vagrant plugin install MODULE-NAME`*

* [List of available Vagrant plugins from GitHub wiki](https://github.com/mitchellh/vagrant/wiki/Available-Vagrant-Plugins).
* [vagrant-vbguest ★2137](https://github.com/dotless-de/vagrant-vbguest) - autoupdate VirtualBox guest additions (according to VB version).
* [vagrant-hostsupdater ★923](https://github.com/cogitatio/vagrant-hostsupdater) - adds an entry to your /etc/hosts file on the host system.
* [vagrant-cachier](http://fgrehm.viewdocs.io/vagrant-cachier/) - share a common package (apt-get, npm, etc.) cache among similar VM instances.
* [vagrant-host-shell ★101](https://github.com/phinze/vagrant-host-shell) - a vagrant provisioner to run commands on the host when a VM boots.
* [vagrant-ansible-local ★60 ⏳2Y](https://github.com/jaugustin/vagrant-ansible-local)  allow provisioning your VM with ansible playbooks directly from the guest VM.
* [sahara ★696 ⏳1Y](https://github.com/jedi4ever/sahara) - easy manage VM state (commit/rollback while experimenting with software stack).


## Helpers / Tools

* [Packer](https://www.packer.io/) - a tool for creating identical machine images for multiple platforms from a single source configuration. For fast infrastructure deployment with multi-provider portability.
* [Veewee ★4074](https://github.com/jedi4ever/veewee) - a tool for easily (and repeatedly) building custom Vagrant base boxes, KVMs, and virtual machine images.
* [Vagrant plugin for ZSH shell](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#vagrant) - auto-complete for commands, task names, box names and built-in documentation.
* [CLI Vagrant Manager ★5](https://github.com/MunGell/vgm) - simple command-line tool to manage multiple vagrant boxes

## Desktop tools

* [Vagrant Manager](http://vagrantmanager.com/) for OS X.

## Web services

*To generate Vagrantfile with automated provisioning scripts.*

* [Phansible](http://phansible.com/) - provides an easy to use interface that helps you generate Ansible Playbooks for PHP based projects.
* [PuPHPet](https://puphpet.com/) - a simple GUI to set up virtual machines for <s>PHP</s> Web development.
* [Protobox](http://getprotobox.com/) - PuPHPet analog, but uses own installer with YAML configuration format to control everything that is installed on the virtual machine.
* [Rove](http://rove.io/) - a service that allows you to pregenerate typical Vagrant builds.

## Proxy services

*To proxy your local web server and make it publicly available over the internet.*

* [Vagrant share](https://www.vagrantup.com/docs/share/) - allows you to share your Vagrant environment with anyone in the world.
* [nip.io](http://nip.io) - a magic domain name that provides wildcard DNS
for any IP address.
* [ngrok](https://ngrok.com/) - tool to create secure tunnels to expose a local server behind a NAT or firewall to the internet.
* [proxylocal.com](http://proxylocal.com) - proxy your local web-server and make it publicly available over the internet.
* [localtunnel.me](https://localtunnel.github.io/www/) - assign you a unique publicly accessible url that will proxy all requests to your locally running webserver.

## Tutorials

* [Getting Started With Vagrant](http://www.thisprogrammingthing.com/2013/getting-started-with-vagrant/) by This Programming Thing.
* [Getting started with Vagrant - automated dev servers deploy and provisioning.](http://stdout.in/en/post/getting_started_with_vagrant_automated_dev_servers_deploy_and_provisioning)
* [Working with Advanced Vagrant features in PhpStorm.](http://confluence.jetbrains.com/display/PhpStorm/Working+with+Advanced+Vagrant+features+in+PhpStorm)
* [Sharing Your Virtual Machine on the Web with Vagrant Share](https://scotch.io/tutorials/sharing-your-virtual-machine-on-the-web-with-vagrant-share).

## Books

* [Vagrant: Up and Running](https://www.amazon.com/Vagrant-Up-Running-Mitchell-Hashimoto/dp/1449335837) by Mitchell Hashimoto.
* [Vagrant CookBook](https://leanpub.com/vagrantcookbook) by Erika Heidi.

## Popular readymade environments

* [Vagrantpress ★767](https://github.com/vagrantpress/vagrantpress) - development environment for creating and modifying WordPress sites.
* [Varying Vagrant Vagrants ★3777](https://github.com/Varying-Vagrant-Vagrants/VVV) - An open source Vagrant configuration focused on WordPress development.
* [Joomla-Vagrant ★131](https://github.com/joomlatools/joomlatools-vagrant).
* [VDD](https://www.drupal.org/project/vdd) - Vagrant Drupal Development.
* [Drupal VM](https://www.drupalvm.com/) - A VM for local Drupal development, built with Vagrant + Ansible
* [Try Yii2 ★46 ⏳1Y](https://github.com/iJackUA/try-yii2) - try Yii2 with Vagrant VM + Ansible provisioning = Complete readymade virtual server playground.
* [Laravel4-Vagrant ★510 ⏳2Y](https://github.com/bryannielsen/Laravel4-Vagrant) - run Laravel 4 inside a Ubuntu 12.04 Vagrant Virtual Machine w/PHP 5.5.
* [OpenStack on Ansible with Vagrant ★215](https://github.com/openstack-ansible/openstack-ansible).
* [Laravel Homestead](https://laravel.com/docs/master/homestead) - Official Vagrant Box for Laravel development, based on Ubuntu 16.04 LTS, PHP 7, Nginx, and multiple database platforms.
* [Scotch Box](https://scotch.io/bar-talk/announcing-scotch-box-2-0-our-dead-simple-vagrant-lamp-stack-improved) - Simple Vagrant Box with [LAMP](https://en.m.wikipedia.org/wiki/LAMP_%28software_bundle%29) stack, plus some useful extras, based on Ubuntu 14.04 LTS.


## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Ievgen Kuzminov](http://stdout.in/) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="http://github.com/iJackUA/awesome-vagrant">iJackUA/awesome-vagrant</a> with ranks
</p>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>