# NOTE : this pseudo notes were made during the class 
## day -01
### kali-linux-2024-VMware
***passwd = ab.......**

garuda Linux

blackarc Linux

--------------------------------------------
## day-02 

ls
pwd

nat 
lan wan 
arc

sudo apt update
sudo apt upgrade
sudo passwd kali - change passwrd
sudo su  - switch user

chmod 

--------------------------------------------------
## day -03

day-01/README.md

#abhijeer
## cyber
####day 1

```pthon

  code
```
[kali.org]{http....}

github---Hackwithvyshu
kerelahacker

basic of GitHub
create a repose
create dir

##index
 [day-01]{http..} intro of cyber+fundamentals

 Below are **rough, classroom‑style notes**—messy on purpose, like quick jottings you might scribble while the trainer talks. They follow the 30‑day plan and match the loose tone of your first three days.

---

## day‑04

```
CIA ➔ conf / integ / avail  
ex – https vs http (lock icon)  
hash = integrity check (sha256sum file.iso)  
uptime = availability  
```

layers = “onion” diagram drawn on board 🧅

---

## day‑05

```
firewall ext → ids → host AV → strong pwd → MFA  
“defense in depth” = many nets to catch fish 🎣  
risk = threat x vuln x impact  (simple math)  
```

homework: list 3 threats at college lab

---

## day‑06

```
risk register sheet (excel)  
crit server unpatched → high risk 🔴  
wifi guest same as prod → med risk 🟠  
```

cmd: `nmap -sV 192.168.1.0/24`

---

## day‑07

**quiz day**
kahoot code 992733 ➔ top 3 get stickers 🏆
review phishing vs vishing

---

## day‑08

```
pass‑phrase >8 words  
manager = bitwarden  
crunch 8 10 abcDEF12 => pw list  
```

live demo ‑ john the ripper cracking old hash

---

## day‑09

```
MFA setup  
google Auth app scan QR  
backup codes txt -> keep offline  
u2f key demo (yubikey)  
```

---

## day‑10

```
malware zoo link (teacher usb) –> vm only!  
virus vs worm vs trojan table  
taskmgr → strange .exe → upload to virustotal  
```

---

## day‑11

```
clamav install  
freshclam update  
clamscan ‑r ~/Downloads  
quarantine folder /opt/virusbin  
```

note: keep defs fresh!

---

## day‑12

```
net basics  
ip a          # show addr  
ports: 80 http, 443 https, 22 ssh  
tcp vs udp beer vs pizza analogy 🍺🍕  
```

---

## day‑13

```
IDS = snort  
rule: alert icmp any any -> any any (msg:"ping!")  
IPS = suricata inline  
vlan 10 students / vlan 20 admin  
```

---

## day‑14

lab:

1. wireshark capture http login → see creds (no tls)
2. eicar test file, AV pops ✅

---

## day‑15

```
web stack recap  
GET /index.php?id=1' OR '1'='1  (sql inj)  
sanitize = prepared stmt  
```

browser dev‑tools shortcut F12

---

## day‑16

```
XSS: <script>alert('hi')</script>  
DOM‑based vs stored  
CSRF = auto POST while user logged in  
token in hidden field fixes  
```

---

## day‑17

```
owasp top10 flyer pdf  
rule: NEVER trust user input!  
lint code → bandit for python  
```

---

## day‑18

```
IAM  
authN = who you are  
authZ = what you can do  
AWS iam users / groups demo  
```

---

## day‑19

```
RBAC chart  
role: HR‑mgr → edit_salary = yes  
CLI: usermod ‑aG hr alice  
```

---

## day‑20

```
IR steps: prep‑id‑contain‑erad‑recover‑lessons  
phone tree sheet posted on wall  
```

---

## day‑21

table‑top drill: “student laptop ransomware”
write incident report.md (who/what/when)

---

## day‑22

```
SIEM = splunk free 500MB/day  
add syslog source 514/udp  
search: index=net src_ip=192.168.*  
```

---

## day‑23

```
UEBA flags: impossible travel 2min 🇮🇳→🇺🇸  
spike in admin cmds at 3 AM  
```

---

## day‑24

```
pentest phases  
recon → whois example.com  
scan  – nmap -sC -sV  
exploit – msfconsole use exploit/multi/…  
```

---

## day‑25

```
nessus essential scan 1 host  
CVSS 9.8 = patch NOW  
export .nessus report  
```

---

## day‑26

diagram DMZ:

```
internet -> fw -> DMZ(web) -> fw -> LAN(db)  
jumpbox ssh only  
```

VLAN tag 30 for CCTV cams

---

## day‑27

```
cloud shared resp: AWS sec of cloud / you sec in cloud  
enable s3 versioning + bucket policy deny public *  
```

---

## day‑28

```
APT cycle: spear‑phish → foothold → lateral → exfil  
group names: APT29 “Cozy Bear”, Lazarus  
mitre attack matrix link  
```

---

## day‑29

mini‑project steps

```
target: metasploitable2 VM  
nmap full scan  
searchsploit vsftpd 2.3.4  
exploit, get shell, write report.md  
```

---

## day‑30

wrap‑up

* push all notes to GitHub
* README badges added
* next path: tryhackme, HTB, Sec+ exam

---


