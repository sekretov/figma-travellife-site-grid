landing page figma
=========

## Setup

1. On ubuntu server(or another linux server).

```bash
python -m SimpleHTTPServer 8012(or another port)

```

2. On Heroku or other Cloud PaaS platform

```bash
https://devcenter.heroku.com/articles/heroku-cli

Login ssh.
Login heroku:
$ heroku login -i

$ heroku plugins:install heroku-cli-static

$ heroku create name_site( as create new app in heroku site)

$ heroku buildpacks:set https://github.com/hone/heroku-buildpack-static -a name_site

$ heroku static: init

further ask the question, you need to write:            public  (used directory: public)

[enter]
[enter]

$ heroku static:deploy - a new_site (start the virtual server =) in the end of page has link on this site:
https://new_site.herokuapp.com/ )  
```

```bash
On linux server must be files in public directory:

index.html logo.png styles.css 

```



## Credits

Sekretov Maksim Vasilievich <maximsecret10@gmail.com>

