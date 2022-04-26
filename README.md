# Docker
<br>

## Why use Docker ?
<br>
<p>Docker makes it really easy to install and run software without worrying about setup or dependencies.</p>
<br>

## What is Docker ?
<br>
<p>Docker is a platform or ecosystem around creating and running containers. </p>
<br>

## What is Image ?
<br>
<p>An image is a single file with all dependencies and configuration required to run a program.</p>
<br>

## What is a Container ?
<br>
<ul>
<li>Container is an instance of an image to run a program. It’s a standardised unit of software . A package of code and dependencies to run that code. </li>
<li>The same container always yields the exact same application and execution behaviour no matter where or by whom it might be executed.</li>
</ul>
<br>

## Installing Docker on Ubuntu
<br>
<p>Use this command to install docker on ubuntu:</p>
<br>

**sudo apt-get install docker.io -y**

<br>
<p>Thereafter use these commands to add your user to docker group:</p>
<br>

**sudo usermod -aG docker ${USER}**
**sudo su ${USER}**

<br>

## Namespacing
<br>
<p>Isolating resources per process or group of processes.</p>
<br>

## Control Groups (cgroups)
<br>
<p>Limit amount of resources per process.</p>
