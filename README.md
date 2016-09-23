This image is Vim application with Vdebug, based on [haron/vim](https://hub.docker.com/r/haron/vim/)

Command to run vim container:
```
sudo docker run -i -t --name my-vim -v ~/:/home/dev/src haoling/vim-vdebug
```

and Press F5 to wait for connect from debugger.
Use with xdebug, etc...
