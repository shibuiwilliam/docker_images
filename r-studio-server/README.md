This docker image runs R Studio Server on CentOS7.
To start the docker container, run the following code.

```
docker pull shibui/r-studio-server
docker run -it -d -p 18787:8787 --privileged --name rss shibui/r-studio-server /sbin/init
```

Once you run the code, you are ready to use R Studio Server, a server-side R Studio, on your web browser.
The R Studio Server is up on 18787 port, so open http://your ip address:18787 .
There you are going to see the sign in page.
The username and password are both "ruser".

Please refer to the following for dockerhub.

https://hub.docker.com/r/shibui/r-studio-server/


For more about R Studio Server, refer to the following websites.

https://www.rstudio.com/products/rstudio/

https://support.rstudio.com/hc/en-us

https://blog.rstudio.org/


Thanks.
