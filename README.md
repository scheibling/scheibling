# Good day!

## whoami
```bash
$ whoami
lars

# My name is Lars, and I'm a software developer/DevOps Engineer.
# I currently live in Sweden, and my free time is currently mostly spent messing around with SSH Certificates.
# You'll find some of my products in my organization (scheiblingco.github.com), mostly because I really like codespaces
# and haven't been invited to the public beta yet.
```

## whereis
```bash
$ whereis scheibling
scheibling: https://github.com/scheibling
            https://github.com/scheiblingco
            https://scheibling.se/category/blog
            https://docs.ssosh.io
```

## capabilities
```bash
$ ls -al /usr/share/doc/capabilities
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 apache2
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 nginx
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 php7.4
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 php7.4-fpm
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 php8.0
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 php8.0-fpm
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 php8.1
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 php8.1-fpm
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 python2.7
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 python3.7
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 python3.9
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 mono
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 mysql
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 mariadb
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 sqlcmd
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 bash
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 code
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 docker
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 docker-compose
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 haproxy
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 ssh
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 oauth2
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 openidconnect
-rwxr-xr-x  1 root root     5479736 Apr 1  2021 saml2
```

```powershell
> ls C:\Users\scheibling\dev\
Directory: C:\Users\scheibling\dev\

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d----          2022-04-01    08:01                .NET4.8
d----          2022-04-01    08:01                .NET6.0
da---          2022-04-01    16:07                Powershell
d----          2022-04-01    11:21                Pwsh
d----          2022-04-01    09:03                SQL Server
d----          2021-04-01    09:38                Visual Studio 2021
da---          2022-04-01    08:46                Visual Studio Code
```

## find /usr/share/doc -type f -name copyright -exec grep "License\:" {} + | cut -f3 -d: | sort -u
I usually publish all of my software under GPLv3, meaning you're free to use all of my software commercially and non-commercially, you can modify and distribute it, 
but i'd appreciate if you included a link to the repo you borrowed code from, and maybe sent a PR if you've improved it in some way. <br>
If you wanna use it commercially or distribute it under a different license, I'd be happy to talk to you about it and we might be able to come to a solution. <br>
I'll probably want some contribution to the codebase of the project you're going to be using in return though.
