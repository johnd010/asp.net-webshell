# webshell

This little web.config is a great resource for ASP.net web servers that you can upload files to.

The web.config essentially creates a webshell that allows you to get RCE.

The most functional method of using this for me has been with curl as such:

curl http://0.0.0.0/upload_dir/web.config?cmd=dir
