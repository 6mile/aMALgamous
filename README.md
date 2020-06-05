# aMALgamous<br />
![Alt MM](/imgs/aMALgamous.png)
aMALgamous is a collection of payloads, shells, and malware generation. As well as a collection of tips and tricks that I have collected over the years of penetration testing.

![GitHub Logo](/imgs/aMAL.png)

## Install
```
git clone https://github.com/Marantral/aMALgamous.git
cd aMALgamous 
sudo ./setup.sh 

You have to make sure that the dpkg --add-architecture i386 worked and you can install x86 packages
```
## Run/Operate
```
python3 aMALgamous.py
```
#### Main Menu <br />
![Alt MM](/imgs/1.png)

#### Malware Menu <br />
![Alt Mal](/imgs/2.png)

#### Shell Menu <br />
![Alt She](/imgs/3.png)

#### Web Help Menu <br />
![Alt Web](/imgs/4.png)

**All malware will be placed in aMALgamatiom/current with old malware being placed in an arcive folder.** <br />

#### Index
The output is numbered based on function.
- 000-009 --> 32bit basic meterpreter payloads 
- 010-019 --> 64bit basic meterpreter payloads 
- 020-029 --> 64bit basic Shell payloads 
- 030-099 --> Saved for future development 
- 100-199 --> Python payloads 
- 200-299 --> MAC payloads 
- 300-319 --> ICMP and DNS payloads 
- 320-329 --> Regsrv32 32bit meterpreter payloads 
- 330-339 --> Regsrv32 64bit meterpreter payloads 
- 340-349 --> Regsrv32 32bit shell payloads 
- 350-359 --> Regsrv32 64bit shell payloads 
- 370-399 --> Saved for future development 
- 400-409 --> InstallUtil payloads
- 410-419 --> MSBuild payloads 
- 420-429 --> PresentationHost payloads
- 430-439 --> RegAsm payloads 
- 440-449 --> RegSvcs payloads 
- 450-900 --> Saved for futre development

- Custom Malware Creation Help 

#### Shell Payloads
- BASH Reverse Shell --------- (Linux|Unix|Mac)
- PERL Reverse Shell --------- (Linux|Unix|Mac)
- PERL Reverse Shell --------- (Windows)
- PowerShell Reverse Shell --- (Windows)
- Python Reverse Shell ------- (Linx|Unix|Mac)
- Python Reverse Shell ------- (Windows)
- PHP Reverse Shell ---------- (Linux|Unix|Mac)
- Ruby Reverse Shell --------- (Linux|Unix|Mac)
- Ruby Reverse Shell --------- (Windows)
- Golang Reverse Shell ------- (Linux|Unix)
- Awk Reverse Shell ---------- (Linux|Unix)
- Java Reverse Shell --------- (Linux|Unix)
- Java Reverse Shell --------- (Windows)
- OpenSSL Shell -------------- (Linux|Unix|Mac)
- NetCat MAC Shell ------------(Mac) 

#### Web Payload Help
- XSS Payloads -----(Cross Site Scripting)
- XXE Payloads ------(XML External Entity)
- SSTI Payloads------(Server Side Template injection)


***********Functions to Add************ 
1. Add automatic Web and SMB Shares on attack box
2. Add Encoding section..
3. Expand Malware examples
4. Add more web application functionality 
5. Add Domain helps
6. Add priv esc helps 

Thanks to all of the TidePod :+1:

