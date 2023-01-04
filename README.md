<div align="center">

# `HackINI-2k22`

<h4>
  Write-ups of the challenges I solved in the HackINI-2k22 ctf challenge
</h4>

<!-- Badges -->
![GitHub Repo stars](https://img.shields.io/github/stars/nemo256/HackINI-2k22?style=for-the-badge)
![Maintenance](https://shields.io/maintenance/yes/2022?style=for-the-badge)
![License](https://shields.io/github/license/nemo256/HackINI-2k22?style=for-the-badge)

<!-- Demo image -->
![Banner](banner.png)

</div>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Project Structure 📁](#project-structure)
* [Credits 🤝](#credits)
* [License 📑](#license)

## Project Structure 📁

```
HackINI-2k22/
├── forensics/
│   ├── lies               # extract information from an image
│   └── smurf              # analyze ICMP packets from capture file using wireshark
├── jail/
│   ├── jsandbox           # escape regex pattern to exploit (call) a function
│   └── less               # escape the less command
├── linux/
│   ├── diff               # utilize the diff command to print file contents
│   ├── nutshell1          # use echo to print a file from double read command (zsh)
│   ├── nutshell2          # exploit the touch command to create a file with different BIRTH date
│   ├── nutshell_supreme   # escape double read command (nutshell1) and regex pattern, then, sl command to return a success code using escape characters
│   ├── remote             # inject commands through ssh
│   └── welcome            # search for file that modifies the welcome message
├── web/
│   ├── whois              # escape regex pattern to run a command on the server side
│   └── whois-fixed        # escape regex pattern to run a command on the server side
├── AUTHORS
├── LICENSE
├── banner.png
└── README.md
```

## Credits 🤝
- Thank you to shelmates https://ctf.shellmates.club/ for organizing this event.
- Thank you to all the AnonyBlasBlas team members for participating.

## License 📑
- Please read [HackINI-2k22/LICENSE](https://github.com/nemo256/HackINI-2k22/blob/master/LICENSE).
