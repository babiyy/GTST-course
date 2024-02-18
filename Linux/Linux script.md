- ### Script installation 
To download from GitHub So we can download and use it. For this purpose git have a feature called ‘clone’
- `git clone <link_of_the_script_from_github>
- python git clone https://github.com/python/cpython.git
- `pip install -r requirments.txt 
- Go : to install go modules `go install <modulename>`
- Ruby : to install ruby modules `gem install<modulename>`
Python: to install python modules we use ->
` pip install <modulename>
- `pip instll term 
- command 'pip' not found, but can be installed with:
`sudo apt install python3-pip`
### GO packge installation

There are 2 installation methods.
- Old version
-  `go get github.con:capotej/groupcache-db-ebperiment.git`
-  New version
-  Downloading the package      `go install github.com/lc/gau/v2cmd/gau@latest`
-  Moving the file to /usr/bin(  the default download place is
`/home/user/go/bin`
sudo mv filename /usr/bin
#### Errors you may encounter
$ sudo apt edit-sources
Ctrl + c = stop run    (Cht-gpt )
###### Help
$ `awk -h, -help, --help`
#### Linux Processes & Services
As we interact with Linux, we create numbered
instances of running programs called
“processes”
- `ps <
- `ps -A- <`
- `ps -u username <
- `PID- Process ID <
###### To stop process
- `KIll -19 PID <` to stop the process
- `kill -18 PID <` to resume the process we stopped
- `kill -9 PID <`To stop a process immediately there are 31 options.
`$ :top <    
`$: htop < `error(sudo apt install binutils)
###### Foreground / background
Thus far, we have run commands at the prompt and waited for them to complete. We
call this running in the “foreground.”
Use the “&” operator, to run programs in the “background” or press ^Z
`$ nano takemel.txt& <
To get the background process back to foreground
` $ fg <`
To stop a process going inside your shell just press ^C

#### Null device
/dev/null - Redirects output to nowhere.
● If you want to ignore output, you can send it to the null device, /dev/null.
● The null device is a special file that throws away whatever is fed to it.
● You may hear people refer to it as the bit bucket.
● If you do not want to see errors on your screen and you do not want to save them to a
file, you can redirect them to /dev/null
● On shell output there are 2 things.
- STDERR = 2
- STDOUT = 1
● To redirect the errors from a command result we do
`command 2> filename =>` here if you check the file you saved on it have errors only
● To redirect the error-FREE output
`command 1>` filename
● So if we redirect our commands output to /dev/null we will get error free result
`command 2> /dev/null
