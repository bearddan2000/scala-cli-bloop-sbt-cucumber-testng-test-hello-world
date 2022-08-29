# scala-cli-bloop-sbt-cucumber-testng-test-hello-world

## Description
A POC for bloop-sbt app using testng.
Writes test results to console
and html. The html for cucumber report is dumped
to the screen.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- scala
- bloop-sbt
  - testng
  - cucumber

## Docker stack
- hseeberger/scala-bloop-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Build code concept](https://github.com/bloop-sbt/sbt-cucumber)
