---
layout:             'project'
title:              'SensioLabs Security Checker'
authors:            ['Fabien Potencier'] 
tags:               ['security', 'composer', 'vulnerabilities checker', 'cli', 'online service'] 

website:            {url: 'https://security.sensiolabs.org/'}
license:            {url: 'https://github.com/sensiolabs/security-checker/blob/master/LICENSE', label: 'MIT License'}
demo:               {url: 'https://security.sensiolabs.org/check'}

github:             {name: 'sensiolabs/security-checker'}
packagist:          {name: 'sensiolabs/security-checker'}          
dockerhub:          [{name: 'phpqa/security-checker'}] 

dependencies:       []
phar:               {url: {'No HTTPS': 'http://get.sensiolabs.org/security-checker.phar'}}

---

[{{ page.title }}]({{ page.url | absolute_url }}) is a command line tool that checks if your
application uses dependencies with known security vulnerabilities.
 
<!--more--> 

It uses the [SensioLabs Security Check Web service][1] and the [Security Advisories Database][2].

[1]: http://security.sensiolabs.org/
[2]: https://github.com/FriendsOfPHP/security-advisories
[3]: http://get.sensiolabs.org/security-checker.phar