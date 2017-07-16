we have a server (basically a computer somewhere that we can access)

•the server is always on (because we pay for it)
•we have users on the server
•users can log into the server and see different files
•in order for the server to become a web server (meaning people can type in addresses) and view the files for those websites, we need to install a web server

To create a web server, we simply need to install a web server. There are two very famous web servers: apache and nginx. Installing either of them onto our server and then making configuration files for each website and then turning it on will allow our websites to run.

Web servers are basically software that run on top of a computer (our server) that do all the heavy lifting:
•when someone types in our website name (assuming we own the domain), it correctly goes to our server
•when the server receives this request, the web server determines which folder to spit out (based on the website name, if there are multiple)

our server has nginx running on your website domain ayaansyed.com

# How do websites work
Each domain has an associated nameserver (NS). What basically this means is that when you type in the domain, that server figures out what to do with what you typed.

Our nameserver is DigitalOcean because that's where our server is hosted.
So anyytime someone types in ayaansyed.com, it goes to the digitalocean nameserver.

This name server then knows we own the domain so based on that it redirects to our server.
