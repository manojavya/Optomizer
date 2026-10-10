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
After a new release is releasesd only that release and the previous release will be supported for pull request. Any older versions will be deemed outdated, yet will be accepted if it is of critical importance.

# Safety Protocols I embedded in the app
Instead of using traditional `sudo` on Linux and MacOS I have put safer GUI alternatives like `pkexec` and `osascript`.

I didnt let Java's ProcessBuilder run the command directly instead I've done `sh -c <code>` for a safer environment and better debugging is that in Linux and Windows I have put `cmd.split("");` so that the commands wont get messed up or joint therefore reducing error rates. 

# Security
1. In no case shall the developer be held liable to any damage caused to the system by the usage of this application.
2. Always read the License before proceeding to the application.
3. This application is an original and authentic application built from scratch by one developer only.
4. Feel free to review code and distribute it with accordance to the GNU GPL3.0 Terms and Conditions.
5. System may be effected due to the options such as High Priority and Low priority or Kill process but this is not caused by the application it self it may be a side effect of a broken system command or a user judgement error.
6. Do not try to alter the state of a process without knowledge of what the process is as it may cause system errors and damage to system software.
