# sshalpine

<p align="center">"<i>If you have a goal, then you will find a way to achieve it.</i>"</p>

<h4 align="center">ssh in alpine run docker</h4>

<br>

<p align="center">
  <a href="https://github.com/gaoljhy/sshalpine/tree/master">
    <img src="https://img.shields.io/badge/Branch-master-green.svg?longCache=true"
        alt="Branch">
  </a>
  <a href="https://github.com/gaoljhy/sshalpine/pulls">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?longCache=true"
        alt="Pull Requests">
  </a>
  <a href="https://github.com/gaoljhy/sshalpine/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg?longCache=true"
        alt="License">
  </a>
</p>

<div align="center">
  <sub>Created by
  <a href="http://grj321.com">gaoljhy</a> and
  <a href="https://github.com/gaoljhy/sshalpine/contributors">
    contributors
  </a>
</div>

<br>

****


A alpine with ssh in docker Container

+ [dockerhub](https://hub.docker.com/r/adminhub/sshalpine)

+ [github](https://github.com/gaoljhy/sshalpine)

## Usage

### Latest

1. pull container 
    `docker pull adminhub/sshalpine:latest`
2. run  Container
    `docker run -d -p 10022:22 --name ssh_alpine adminhub/sshalpine`
  > or add privileged , isolate ....
3. ssh interface
    `ssh root@localhost -p 10022`

> default password `sshalpine`
