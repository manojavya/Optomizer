# Security Policy
Pull Requests with unneccesary modifications in system commands like `renice` will not be accepted unless important.

All Pull requests will be throughly checked by the developer if compliant the pull request will be accpted.
## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 3.1.0   | No                 |
| 3.2.0   | No                 |
| 3.3.0   | Yes                |
| 3.4.0   | Yes                |


## Reporting a Vulnerability

Feel free to report vulnerabilities 🙂.

# Pull Requests life cycle:
After a new release is releasesd only that release and the previous release will be supported for pull request. Any older versions will be deemed outdated!

# Safety Protocols I embedded in the app
Instead of using traditional `sudo` on Linux and MacOS I have put safer GUI alternatives like `pkexec` and `osascript`.

I didnt let Java's ProcessBuilder run the command directly instead I've done `sh -c <code>` for a safer environment and better debugging is that in Linux and Windows I have put `cmd.split("");` so that the commands wont get messed up or joint therefore reducing error rates. 
