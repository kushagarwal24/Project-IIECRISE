mkdir Project@IIEC-RISE

#Put all the content inside the directory.

cd Project@IIEC-RISE

#This is very simple NGINX website that allows a user to send a tweet. #It's mostly used as a sample application for Docker 101 workshops. #To use it:

Build it: docker build -t linux_tweet_app .

Run it: docker container run --detach -p 80:80 linux_tweet_app

#Open the browser :80

#CLick on tweet#Docker #Enter your credentials and use it.
