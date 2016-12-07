# MCAT
NETCAT alternative  (ref from Black Hat Python)

#ABOUT
This is an Alternative version of netcat developed in Python for those who dont have netcat ..it has lots of features  other than eimple version of netcat, mainly developed for penetration testers and malware researchers ... and it is also converted in standalone .exe file so just use it on any windows machine without any problem.

Reference is taken from Black Hat Python Book.

#USAGE

         "Usage: MCAT.py -t target_host -p port"
         "-l --listen                - listen on [host]:[port] for incoming connections"
         "-e --execute=file_to_run   - execute the given file upon receiving a connection"
         "-c --command               - initialize a command shell"
         "-u --upload=destination    - upon receiving connection upload a file and write to [destination]"
         "Examples: "
         "MCAT.py -t 192.168.0.1 -p 5555 -l -c"
         "MCAT.py -t 192.168.0.1 -p 5555 -l -u=c:\\target.exe"
         "MCAT.py -t 192.168.0.1 -p 5555 -l -e=\"cat /etc/passwd\""
         "echo 'ABCDEFGHI' | ./MCAT.py -t 192.168.11.12 -p 135"
