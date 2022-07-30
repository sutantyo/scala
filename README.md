# Learning Scala

## Installation

Installed Scala following the instructions on https://www.scala-sbt.org/1.x/docs/Installing-sbt-on-Linux.html (using WSL on Windows)
using `sdkman`. Here are the steps:
- `sudo apt-get install zip`
- `sudo apt-get install unzip`
- (restart terminal)
- `curl -s "https://get.sdkman.io" | bash` (installing sdkman)
- (restart terminal)
- `sdk install java $(sdk list java | grep -o "\b8\.[0-9]*\.[0-9]*\-tem" | head -1)`
- `sdk install sbt`
