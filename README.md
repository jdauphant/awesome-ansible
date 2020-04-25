# Awesome Ansible

## @jdauphant : I don't have time to manage anymore this repository. Don't hesitate to fork and made your own version.

A collaborative curated list of awesome Ansible resources

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Contents

- [Books](#books)
- [Roles](#roles)
- [Playbooks](#playbooks)
- [Tools](#tools)
- [Resources](#resources)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->
---
## Books

*Books regarding Ansible*

- [Ansible Configuration Management - Second Edition](https://www.packtpub.com/networking-and-servers/ansible-configuration-management-second-edition)
- [Ansible for DevOps](https://www.ansiblefordevops.com)
- [Ansible Playbook Essentials](https://www.packtpub.com/networking-and-servers/ansible-playbook-essentials)
- [Ansible - Up and Running](http://shop.oreilly.com/product/0636920035626.do)
- [Learning Ansible](https://www.packtpub.com/networking-and-servers/learning-ansible)
- [Learning Ansible 2 - Second Edition](https://www.packtpub.com/networking-and-servers/learning-ansible-2-second-edition)
- [Mastering Ansible - Second Edition](https://www.packtpub.com/networking-and-servers/mastering-ansible-second-edition)
- [OpenStack Administration with Ansible](https://www.packtpub.com/virtualization-and-cloud/openstack-administration-ansible)

## Roles

*Roles for Ansible*

- Java : [Github](https://github.com/silpion/ansible-java) / [Galaxy](https://galaxy.ansible.com/list#/roles/457)
- MySQL : [Github](https://github.com/ANXS/mysql) / [Galaxy](https://galaxy.ansible.com/list#/roles/509)
- Nginx : [Github](https://github.com/jdauphant/ansible-role-nginx) / [Galaxy](https://galaxy.ansible.com/list#/roles/466)
- os-hardening : [Github](https://github.com/dev-sec/ansible-os-hardening) / [Galaxy](https://galaxy.ansible.com/dev-sec/os-hardening/)
- PostgreSQL : [Github](https://github.com/ANXS/postgresql) / [Galaxy](https://galaxy.ansible.com/list#/roles/512)
- Redis : [Github](https://github.com/DavidWittman/ansible-redis) / [Galaxy](https://galaxy.ansible.com/detail#/role/730)

## Playbooks

*Playbooks for Ansible*

- [Ansible Examples](https://github.com/ansible/ansible-examples) - This tutorial presents ansible step-by-step.
- [Ansible Desktop](https://github.com/kalos/ansible-desktop)
- [Ansible Tutorial](https://github.com/leucos/ansible-tuto)
- [Ansible Vagrant Examples](https://github.com/geerlingguy/ansible-vagrant-examples)
- [DebOps](https://docs.debops.org/en/master/ ) - Your Debian-based data center in a box. A collection of Ansible playbooks, scalable from one container to an entire data center.
- [fgci-ansible](https://github.com/CSCfi/fgci-ansible) - Collection of the Finnish Grid and Cloud Infrastructure Ansible playbooks (CentOS).
- [FreeBSD](https://github.com/jdauphant/ansible-freebsd-playbooks) - Playbook example for FreeBSD.
- [Hadoop](https://github.com/analytically/hadoop-ansible) - Ansible playbook that installs a Hadoop cluster, with HBase, Hive, Presto for analytics, and Ganglia, Smokeping, Fluentd, Elasticsearch and Kibana.
- [Heartbleed OpenSSL Patch](https://github.com/jdauphant/patch-openssl-CVE-2014-0160) - A simple playbook that update OpenSSL for Debian system.
- [Mac Development Ansible Playbook](https://github.com/geerlingguy/mac-dev-playbook) - Playbook to install and configure software on a Mac.
- [OpenStack](https://github.com/openstack/openstack-ansible)
- [Rails](https://github.com/j-mcnally/ansible-rails)
- [Sovereign](https://github.com/sovereign/sovereign) - Your own personal cloud.
- [Streisand](https://github.com/StreisandEffect/streisand) - Streisand sets up a new server running L2TP/IPsec, OpenConnect, OpenSSH, OpenVPN, Shadowsocks, sslh, Stunnel, a Tor bridge, and WireGuard. It also generates custom instructions for all of these services. At the end of the run you are given an HTML file with instructions that can be shared with friends, family members, and fellow activists.
- [T.A.D.S. boilerplate](https://github.com/Thomvaill/tads-boilerplate) - Provision and deploy a Docker Swarm cluster to development environment and to production. Infrastructure as Code and DevOps best practices.
- [VPN Deploy](https://github.com/ftao/vpn-deploy-playbook)

## Tools

*Ansible related Tools*

- [Ansible cmdb](https://github.com/fboender/ansible-cmdb) - Takes the output of Ansible's fact gathering and converts it into a static HTML overview page containing system configuration information.
- [Ansible Inventory Grapher](https://github.com/willthames/ansible-inventory-grapher) - creates a dot file suitable for use by [graphviz](http://www.graphviz.org/).
- [Ansible Lint](https://github.com/ansible/ansible-lint) - Checks playbooks for practices and behaviour that could potentially be improved.
- [Ansible Shell](https://github.com/dominis/ansible-shell) - Interactive shell for Ansible with built-in tab completion for all the modules.
- [Ansible Silo](https://github.com/groupon/ansible-silo) - Ansible in a self-contained environment via Docker.
- [Ansible Vim](https://github.com/pearofducks/ansible-vim) - Vim syntax plugin for Ansible 2.0.
- [Ansigenome](https://github.com/nickjj/ansigenome) - Ansigenome is a command line tool designed to help you manage your Ansible roles - scan, standarize documentation and meta files, generate dependency graphs.
- [ARA: Ansible Run Analysis](https://github.com/openstack/ara) - Records Ansible Playbook runs seamlessly to make them easier to visualize, understand and troubleshoot. It integrates with Ansible wherever you run it.
- [AWX](https://github.com/ansible/awx) - AWX provides a web-based user interface, REST API, and task engine built on top of Ansible. It is the upstream project for Tower, a commercial derivative of AWX.
- [Mitogen for Ansible](https://mitogen.readthedocs.io/en/latest/ansible.html) - Uses the [Mitogen](https://github.com/dw/mitogen/) library to execute Ansible playbooks in a more efficient way (decreases the execution time).
- [Molecule](https://github.com/ansible/molecule) - Testing of Ansible roles.
- [OpsTools-ansible](https://github.com/centos-opstools/opstools-ansible) - The project opstools-ansible is to use Ansible to configure an environment that provides the support of [OpsTools](https://wiki.centos.org/SpecialInterestGroup/OpsTools), namely centralized logging and analysis, availability monitoring, and performance monitoring.
- [Phansible](http://phansible.com/) : [Github](https://github.com/phansible/phansible) - Simple generator for Vagrant projects, targeting PHP development environments.
- [Semaphore](https://github.com/ansible-semaphore/semaphore) - Open Source Alternative to Ansible Tower.
- [TD4A](https://github.com/cidrblock/td4a) - Template designer for automation - TD4A is a visual design aid for building and testing jinja2 templates. It will combine data in yaml format with a jinja2 template and render the output.

## Resources

*Useful Ansible resources*

- [Ansible Galaxy](https://galaxy.ansible.com/) - Hub for finding roles.
- [Ansible User Guide](https://docs.ansible.com/ansible/latest/index.html), including [Best Practices](https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html) and [Conventions, tips, and pitfalls](https://docs.ansible.com/ansible/latest/dev_guide/developing_modules_best_practices.html).
- [Ansible Quickref](https://github.com/lorin/ansible-quickref/) - Quick reference to parameters and special variables.
- [Ansible vs Chef](https://tjheeta.github.io/2015/04/15/ansible-vs-chef/)
- [Ansible (Real Life) Good Practices](https://reinteractive.com/posts/167-ansible-real-life-good-practices/)
- [Ansible and Ansible Tower: best practices from the field](https://www.juliosblog.com/ansible-and-ansible-tower-best-practices-from-the-field/)
- [Management of FreeBSD jails through Ansible](https://www.keltia.net/howtos/jail-mgmt-with-ansible/)
- [Packer Provisioning with Ansible](https://www.packer.io/docs/provisioners/ansible-local.html)
- [Vagrant Provisioning With Ansible](https://www.vagrantup.com/docs/provisioning/ansible.html)
