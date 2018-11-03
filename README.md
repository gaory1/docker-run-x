# docker-run-x
Running GUI apps with Docker 

This is a short script that pass required arguments to 'docker run' to run GUI apps. Use it simply by replacing 'docker run' with 'docker-run-x', like this:

docker-run-x image command

docker-run-x firefox

docker-run-x -v $HOME:$HOME vlc

If you encounter problems with certain app, it is recommended to see this: https://github.com/somatorio/docker-desktop

----
用Docker运行图形用户界面程序

这是一个很短的脚本，它把一些必要的参数传给'docker run'以运行图形用户界面程序。使用方法很简单，只需要将'docker run'替换换'docker-run-x'就可以了，像这样：

docker-run-x image command

docker-run-x firefox

docker-run-x -v $HOME:$HOME vlc

如果使用某些特定应用遇到问题，推荐看这个：https://github.com/somatorio/docker-desktop
