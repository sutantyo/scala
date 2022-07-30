# Learning Scala

## Installation

Installed Scala following the instructions on https://www.scala-sbt.org/1.x/docs/Installing-sbt-on-Linux.html (using WSL on Windows).
The first step is to install `sdkman` (https://sdkman.io/), here are the steps on WSL:
- `sudo apt-get install zip`
- `sudo apt-get install unzip`
- (restart terminal)
- `curl -s "https://get.sdkman.io" | bash` (installing sdkman)
- (restart terminal)
- `sdk install java $(sdk list java | grep -o "\b8\.[0-9]*\.[0-9]*\-tem" | head -1)`
- `sdk install sbt`
