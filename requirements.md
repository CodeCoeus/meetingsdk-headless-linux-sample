Enhancements:
1. Add the way to interact with the meeting through messages 
2. Parse through the speech in real time to detect for the trigger word.
3. have support for multiple meeting sessions at once -- so that we donot need multiple instances of this code to be executed for different users

Currect blockers:
1. Building the system - cmake etc issue
2. understanding the libs used and APIs for each of these
3. zoomsdk lib referrences





========

installation issue
1. in main.cpp, hover on the `#include<glib.h>` 'glib.h' file not foundclang(pp_file_not_found)
    1. solution: remove empty `./build/` dir
2. W: [pulseaudio] main.c: This program is not intended to be run as root (unless --system is specified).
3. Need to have container running even after script termination
    1. https://kodekloud.com/blog/keep-docker-container-running/

