<h1 align="center"> SToServer</h1>
<p align="center"> fuck ... use SToServer a tool which take selected file and copied to server using rsync</p>

##
<p align="center"> <img src="/demo.gif" alt="Video Preview" width="500px"> </p>

### How does this work?
This is shell script. It select file using [dmenu](https://tools.suckless.org/dmenu/) and [rsync](https://linux.die.net/man/1/rsync) to tranfer file to server
for selecting it uses simple gnu utils like sed, awk. 

## Requirements
+ curl  `sudo apt install curl`
+ [dmenu](https://tools.suckless.org/dmenu/) - A suckless tool for application launcher. 
+ `git clone https://git.suckless.org/dmenu`

## Installation
cURL stoserver to your **$PATH**  and give execute permission 
```sh
$ sudo curl -sL "https" -o /usr/local/bin/stoserver
$ sudo chmod +x /usr/local/bin/stoserver
```

- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply remove `stoserver` from your **$PATH**, for example `sudo rm -f /usr/local/bin/stoserver`. 

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

