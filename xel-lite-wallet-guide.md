<!-- TITLE: Xel Lite Wallet Guide -->
<!-- SUBTITLE: A quick summary of Xel Lite Wallet Guide -->


# Welcome to XEL!

[![GitHub version](https://badge.fury.io/gh/xel-software%2Fxel-computation-wallet.svg)](https://badge.fury.io/gh/xel-software%2Fxel-computation-wallet)

XEL is a decentralized supercomputer based on cryptography and blockchain technology.

----
## disclaimer

XEL CORE / XELINE IS OPEN-SOURCE SOFTWARE RUNNING ON THE MAIN-NET BUT IS STILL CONSIDERED "BETA" AND MAY CONTAIN BUGS, SOME OF WHICH MAY HAVE SERIOUS CONSEQUENCES. WE THEREFORE DISCLAIM ANY LIABILITY OF ANY KIND FOR ANY DAMAGES WHATSOEVER RESULTING DIRECTLY OR INDIRECTLY FROM THE USE OF THIS SOFTWARE OR OF ANY DERIVATIVE WORK. USE THE SOFTWARE AND THE INFORMATION PRESENTED HERE AT OUR OWN RISK.

----
## Run XEL Lite Wallet from binaries (***recommended for desktops***)

https://github.com/xel-software/xel-lite-wallet/releases/tag/latest

----
## Run XEL Lite Wallet from docker installer (***recommended for servers***)

check the dedicated git project : https://github.com/xel-software/xel-installer-docker

----
## Run XEL Lite Wallet from sources (***recommended for advanced users***)

### dependencies
  - Oracle Java 8 : https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
  - Maven : https://maven.apache.org/install.html

### clone the repository

`git clone https://github.com/xel-software/xel-lite-wallet`
`cd xel-lite-wallet`

### compile it

`mvn package`

### start from the command line:
  - Linux/macOS: `./start.sh`
  - Windows: `run.bat`

***wait for the JavaFX wallet window to open***
***on platforms without JavaFX, open http://localhost:17876/ in a browser***



----
## Improve it

  - we love **pull requests**
  - we love issues (resolved ones actually ;-) )
  - in any case, make sure you leave **your ideas**
  - assist others on the issue tracker
  - **review** existing code and pull requests

----
## Troubleshooting (XEL Reference Software)

  - How to Stop the XEL Server?
    - click on XEL Stop icon, or run `./stop.sh`
    - or if started from command line, ctrl+c or close the console window

  - UI Errors or Stacktraces?
    - report on github
