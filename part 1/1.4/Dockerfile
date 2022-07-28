FROM ubuntu 


RUN apt-get update \ 
    && DEBIAN_FRONTEND=noninteractive \
       apt-get install \
         --no-install-recommends \
         --assume-yes \
         curl



CMD curl "$website"

