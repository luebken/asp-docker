build: 
  docker build -t asp-docker .

run:
  docker run -P asp-docker

Inspired by: http://blogs.msdn.com/b/webdev/archive/2015/01/14/running-asp-net-5-applications-in-linux-containers-with-docker.aspx
