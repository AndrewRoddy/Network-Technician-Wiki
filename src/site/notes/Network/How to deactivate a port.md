---
{"dg-publish":true,"permalink":"/network/how-to-deactivate-a-port/"}
---


# How to deactivate a port

1. `ssh` in using the IP you [[Network/Building an IP\|built]]
	1. `ssh name_stu@XX.XXX.XXX.XX`
2. `conf t` Enter Configuration Mode 
3. `int g1/0/9` Interface with ports at the end 
	1. `int` mode
		1. `int` for one
		2. `int range` for multiple
	2. Add your ports `##/#/#`
		1. p. `#` is what port it is
		2. `g1/0/#` < cisco
		3. `1/1/#` < aruba
		4. `%/1/#` < `%` is the stack number
4. `shut` turns off everything :)
5. `desc DAT_` clear the description
6. `exit` Leave range mode
7. `exit` Leave configuration mode
8. `wr mem` Save our changes to hard storage
9. `exit` leave the `ssh`





