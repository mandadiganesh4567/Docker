FROM almalinux:9
 ADD https://in.bmscdn.com/iedb/artist/images/website/poster/large/jr-ntr-15411-19-09-2017-01-52-16.jpg /usr/share/nginx/html/ntr.jpg
 RUN dnf install nginx -y
 CMD ["nginx", "-g", "daemon off;"]
 RUN echo "<html><body style='background-color:black; color:white; text-align:center;'> <h1>Welcome Ganesh page</h1> <img src='ntr.jpg' width='300'> </body></html>" > /usr/share/nginx/html/index.html