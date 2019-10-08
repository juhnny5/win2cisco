<h1 align="center">WIN2CISCO</h1>
<p align="center">
	Convert a Windows Mac address to Cisco format.
	<br>
	<br>
  <a href="https://github.com/julienbriault/win2cisco/pulls">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?longCache=true" alt="Pull Requests">
  </a>
  <a href="http://www.gnu.org/licenses/">
    <img src="https://img.shields.io/badge/License-GNU-blue.svg?longCache=true" alt="License">
  </a>
</p>

## Usage 
```
Usage: win2cisco [-h] [-m FF:FF:FF:FF:FF:FF]

Convert a Windows MAC address to Cisco

Options:
        -m      specify source mac address
        -h      display help message
        -v      display version

```
## Recovery 
To retrieve the script and give it execution rights, it's easy to use the following commands:
```
git clone https://github.com/julienbriault/win2cisco.git ; cd win2cisco ; chmod u+x win2cisco
```
## Example
You can convert one or more addresses simultaneously.
```
./win2cisco -m "ff:ff:ff:ff:ff:ff ee:ee:ee:ee:ee:ee"  
```

---
Report any type of problems [here](https://github.com/julienbriault/win2cisco/issues)!
