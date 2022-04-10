![image](https://user-images.githubusercontent.com/24763414/162615594-f22742ff-2794-4085-95c6-f98a56f9daa1.png)

# REDOX
REDOX is an automated reconnaissance tool meant for gathering information during penetration testing of web applications.

# Usages 
  
 Grant permission for execute
 $ chmod +x redox.sh
  
# Tool usages
$./redox <IP>
  Demo : $./redox 127.0.0.1

Or you can move it to /usr/local/bin
  
$ mv redox /usr/local/bin 

![image](https://user-images.githubusercontent.com/24763414/162614536-e8c56c00-accb-473d-bebe-4b12c7d52217.png)

  
# Requirements 
  1. nmap
  2. gobuster
  3. whatweb
  4. shodan
  
# Why Redox

  1. Faster
  2. Reliable 
  
# Project Aim :
It will display the open ports, and if any open ports on 80 http are found, it will crawl all directories of the given target. Following that, it detects web technologies such as content management systems (CMS), blogging platforms, statistical/analytics packages, JavaScript libraries, web servers, and embedded devices. Finally, it checks for CVEs (or displays you Vulnerabilities) and then performs doxing (dumping information such as ISP name, city or state name, zip code, location, time zone, and many more) on the host IP.
  
# Creator
  Abubakkar Khan Fazla Rabbi
  (Web Penetration Tester & Security Analyzer)
