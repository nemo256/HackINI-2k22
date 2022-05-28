# HackINI-2k22 ctf challenge write-ups
Write-ups of the challenges I solved in the HackINI-2k22 ctf challenge

![Banner](banner.png)

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Format](#format)
* [License](#license)
* [Credits](#credits)

## Format

```
- Repo
  - forensics
    - lies                    # extract information from an image
    - smurf                   # analyze ICMP packets from capture file using wireshark
  - jail
    - jsandboxs               # escape regex pattern to exploit (call) a function
    - less                    # escape the less command
  - linux
    - diff                    # utilize the diff command to print file contents
    - nutshell1               # use echo to print a file from double read command (zsh)
    - nutshell2               # exploit the touch command to create a file with different BIRTH date
    - nutshell_supreme        # escape double read command (nutshell1) and regex pattern, then, sl command to return a success code using escape characters
    - remote                  # inject commands through ssh
    - welcome                 # search for file that modifies the welcome message
  - web
    - whois                   # escape regex pattern to run a command on the server side
    - whois-fixed             # escape regex pattern to run a command on the server side
  - AUTHORS
  - LICENSE
  - banner.png
  - README.md
```

## License
- Please read HackINI-2k22/LICENSE.
- If you're too lazy to read, do anything you want with this project and don't forget to give credits to me 'nemo256', this repo link or to the team 'AnonyBlasBlas' as it is much appreciated.

## Credits
- Thank you to shelmates https://ctf.shellmates.club/ for organizing this event.
- Thank you to all the AnonyBlasBlas team members for participating.
