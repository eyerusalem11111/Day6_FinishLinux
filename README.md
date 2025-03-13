# Day6_FinishLinux
# Script installation
- git clone <link_of_the_script_from_git>
- eg. git clone https://github.com/rexder26/InitProgram.git
Script module
- scripts asre writen in scritung languages like python,bash,go,ruby...
- to install those we use commandes of
    - for python ->pip install <module name>
     - for requiremants/deoendencies/ file -> pip install -r requirmanta.txt
     - the pip command may not be installed so u may use 'sudo apt install python3.pip'
     - may be current time pipx works
- Go: to install go modules -> go install <modulename>
- go scripts are made with go language. there are two methodes
- 1.old version-> go git github.com:capotej/groupcache-db-experiment.git
- 2. new version-> a. Download the package go install github.com/1c/gau/v2/cmd/gau@lastest
-                             b.Moving the file to/usr/bin(the default download place is /home/ rexder/go/bin)    sudo mv filename_/usr/bin
- to execute the file we use : ./go/bin/filename
- Ruby: to install ruby module ->gem install <modulename>
# To get help on linux 
we use man(manual)->this will give you the whole manual and instruction ofa tool or command.
man <yourcommand>
eg. man awk
/arrow keys for navigation and q for quit/
we use help-> to show options of command
    use one of those options tp use help based on the command->
              <yourcommand> -h
              <yourcommand> -help
              <yourcommand> --help
# Process and service
prosses: running instances of memory.
service: background programs  that starts automatically manually,often for system tasks(also knnown as daemons)
- to get the process running ->ps [option]
- ps -> for program running on my shell
- ps -A ->view all running process
- ps -u username -> view username process
To manage processes on linux
- to stop process
    -kill[option][PID]
     - killall[progarams]
     - kill -19PID->to stop the process
     - kill -18PID->toresume process that was stoped
     - kill -9PID->to stop a process immediately...up to 31 options
     - PID-> process id
     - PPID->parent process id
- top 
- to exist top press (q)
- htop + select+F9->kill
- F3->search
- to exist from htop press F10
# Foreground and Background
- Foreground-> run commands till compilation.
- use the "&" operator to run programs in the background or press (ctrl/^z)
- to make background runner to foreground use command of (fg)
- to stop 
