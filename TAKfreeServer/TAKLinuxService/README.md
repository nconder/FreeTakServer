# How To install FreeTakServer on Linux #
* clone repository with the following command 
```
git clone https://github.com/Tapawingo/TAKlib.git
```

* install python3 with the following command 

```
sudo apt update && sudo apt install python3
```

* enter the TAKLinuxService directory
```
cd freeTak/TAKLinuxService
```
* run the following command to start FTS as a demon with port defined in costant  (default is 8087)
```
sudo python3 beginServerFromLinux.py
```
*  in alternative, not recomended, you can use server.py, setting the port with the parameter -p like that
```
 python3 TAKfreeServer/server.py -p 8089
 ```
 if you run FTS without the demon, the process will depend on the console being open.  it's suggested to use the demon, so that you can close the console.

## Notice ##
> this has been tested with Ubuntu 18.04.4
