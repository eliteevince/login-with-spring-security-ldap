# login-with-spring-security-ldap

## What is ldap?
LDAP is stands for Lightweight Directory Access Protocols, LDAP is internet protocol that can be used for email and other programs to look up information from server.
LDAP is mostly used by medium to large organization, If you belong to one that has LDAP server, you can use it to look up contact info.

Every email program has a personal address book, but how do you look up an address for someone who's never sent you email? How can an organization keep one centralized up-to-date phone book that everybody has access to?
To answer this questions large organizations are agreed to support such standard called LDAP. 

A client program “LDAP-aware” can ask LDAP servers to look up entries in wide variety of ways. LDAP server index all the data in their entries and filter may be used to select just a person or group that you want. And return just a information what you want.

### Ldap with spring-boot
This demo is done by spring-boot, spring-security, and ldap. Here you may learn how to setup and run login page using spring-boot and ldap.

#### step to run this project
- Download this project and unzip in specific directory.
- Import that project in your IDE.
- In resource folder you may find test-server.ldif file, That file is used for ldap configuration (you can change according to your enviroment).
- In application.properties you may found the ldap congifuration with spring-boot (you can change according to your enviroment).
- After configure that files you can able to run this project.
- When project is in running you can see the default login page of spring-security enter the password that you configure in test-server.ldif file.
- If credencial is valid then you must be redirect to default welcome page of spring-security, if credencial is invalid then you get the error message that is Bad credencial.
- Here we set **ee** as username and **eespassword** as password.
- **(Note):-** this configuration is only for local and testing purpose, do to use in production enviroments.
