# avatar_heygen_livekit
Start a web interface in the browser to start a conversation with HeyGen Avatar

Steps:

1) run a docker image

   docker container run -d -p 80:80 -p 443:443 nginx
   
2) load avatar.html into container

   docker container cp avatar.html \<ID\>:/usr/share/nginx/html
   
3) start into the browser

   http://\<IP\>:80/avatar.html
