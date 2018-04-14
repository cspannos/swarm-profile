**What is swarm-personal?**
 
This repository the personal website for Chris Spannos and is hosted on SWARM's serverless peer-to-peer content storage and distribution platform, domain accessible via the Ethereum Name Service (ENS, alternative to DNS) protocol. It is built using HTML5. The theme is "Forty" by HTML5 UP (html5up.net), under the CCA 3.0 license.

**How does it work?**

These instructions assume that you have both Geth and SWARM installed on your machine, that you are running a basic SWARM node and have created a Geth account. One you have your node up, to upload a directory, run the command: 

```
swarm --recursive --defaultpath /path/to/your/directory/index.html --bzzapi http://swarm-gateways.net/ up /path/to/your/directory

```
**Important note:** These instructions are an adaptation from SWARM documentation. It is reccomeded to go to SWARM's original documentation and follow instructions there: https://swarm-guide.readthedocs.io/en/latest/simpleuser.html#how-do-i-upload-and-download 

**Who will use this repo or project?**

The website is built, maintained and administered by Chris. 

**What is the goal of this project?**

It is an experiment in building websites on distributed platforms.
