Firejail ansible playbook
=========================

!["Prompt"](https://raw.githubusercontent.com/gbraad/assets/gh-pages/icons/prompt-icon-64.png)


Deploy firejail on a Fedora workstation


Prerequisite
------------

Make sure you can perform a password-less login to the hosts you want to configure.


Usage
-----

```
$ yum install -y ansible python-dnf
$ ansible-galaxy install -r roles.txt
$ vi hosts
$ ansible-playbook -i hosts deploy_firejail.yml
```


Used roles
----------

  * gbraad.firejail  
    [Galaxy](https://galaxy.ansible.com/gbraad/firejail/), [GitHub](https://github.com/gbraad/ansible-role-firejail) / [GitLab](https://gitlab.com/gbraad/ansible-role-firejail)


Authors
-------

| [!["Gerard Braad"](http://gravatar.com/avatar/e466994eea3c2a1672564e45aca844d0.png?s=60)](http://gbraad.nl "Gerard Braad <me@gbraad.nl>") |
|---|
| [@gbraad](https://twitter.com/gbraad)  |
