# node-10-alpine-pdftk

Basically latest node alpine build is based on the alpine 3.9, which doesn't have pdftk in it. So this docker file helps build images with alpine-3.7 as the base layer and install pdftk, which can be used with nodejs packages pdf-filler etc which have pdftk dependencies. 
