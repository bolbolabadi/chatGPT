## Find real IP behind CDN

+ To find the real IP address of a website behind a CDN (Content Delivery Network), you can use a tool such as the "traceroute" command. Traceroute is a network diagnostic tool that shows the route that a packet of data takes from your computer to the destination website. By using traceroute, you can see the IP addresses of the intermediate servers that the packet passes through on its way to the website, and you can find the IP address of the origin server that is serving the website behind the CDN.
Here is an example of how to use the traceroute command to find the real IP address of a website behind a CDN:
  + Open a command prompt or terminal on your computer.
  + Type the following command and press Enter: traceroute [website-name]
For example, if the website you want to find the real IP address of is "example.com", you would type the following command:

``` traceroute example.com ```

  This command will show the route that a packet of data takes from your computer to the website. The output will show the IP addresses of the intermediate servers that the packet passes through on its way to the website, and it will also show the IP address of the origin server that is serving the website behind the CDN.



+ Another way to find the real IP address of a website behind a CDN is to use a website that provides this information, such as "CDN Planet". CDN Planet is a website that provides information and tools for CDN users and administrators. It provides a tool called the "CDN Finder" that can be used to find the real IP address of a website behind a CDN.
Here is an example of how to use CDN Planet's CDN Finder tool to find the real IP address of a website behind a CDN:
  + Go to the CDN Planet website at https://www.cdnplanet.com/.
  + Click on the "CDN Finder" tab in the top menu.
  + In the "Enter a Domain" field, type the name of the website you want to find the real IP address of and press Enter.
For example, if the website you want to find the real IP address of is "example.com", you would type "example.com" in the "Enter a Domain" field.
The CDN Finder tool will show the real IP address of the website behind the CDN, along with other information such as the CDN provider and the type of CDN used.




+ Another way to find the real IP address of a website behind a CDN is to use the "nslookup" command. Nslookup is a network administration tool that is used to query the Domain Name System (DNS) to find information about a domain name or IP address. By using nslookup, you can find the IP address of the origin server that is serving the website behind the CDN.
Here is an example of how to use the nslookup command to find the real IP address of a website behind a CDN:
Open a command prompt or terminal on your computer.
Type the following command and press Enter: nslookup [website-name]
For example, if the website you want to find the real IP address of is "example.com", you would type the following command:

``` nslookup example.com ```

This command will query the DNS to find the IP address of the website. The output will show the IP address of the origin server that is serving the website behind the CDN.




+ Another way to find the real IP address of a website behind a CDN is to use the "dig" command. Dig is a network administration tool that is used to query the Domain Name System (DNS) to find information about a domain name or IP address. By using dig, you can find the IP address of the origin server that is serving the website behind the CDN.
Here is an example of how to use the dig command to find the real IP address of a website behind a CDN:
Open a command prompt or terminal on your computer.
Type the following command and press Enter: dig [website-name]
For example, if the website you want to find the real IP address of is "example.com", you would type the following command:

``` dig example.com ```

This command will query the DNS to find the IP address of the website. The output will show the IP address of the origin server that is serving the website behind the CDN.




+ Another advanced way to find the real IP address of a website behind a CDN is to use a network traffic analysis tool such as Wireshark. Wireshark is a powerful network protocol analyzer that can be used to capture, analyze, and inspect network traffic. By using Wireshark, you can find the real IP address of a website behind a CDN by analyzing the network traffic between your computer and the website.
Here is an example of how to use Wireshark to find the real IP address of a website behind a CDN:
  + Install and open Wireshark on your computer.
  + In Wireshark, select the network interface that you want to use to capture network traffic.
  + Start the network capture by clicking on the "Start" button.
  + Open a web browser on your computer and go to the website you want to find the real IP address of.
  + Stop the network capture by clicking on the "Stop" button in Wireshark.
  + In Wireshark, use the filter field to filter the captured network traffic by the domain name of the website you are interested in.
For example, if the website you want to find the real IP address of is "example.com", you would type "example.com" in the filter field.
In the filtered network traffic, look for the DNS response packets that contain the IP address of the website. The IP address of the origin server that is serving the website behind the CDN will be in the "Answer" section of the DNS response packet.




+ Another advanced way to find the real IP address of a website behind a CDN is to use a network traffic analysis tool such as tcpdump. Tcpdump is a command-line network traffic analyzer that can be used to capture and analyze network packets. By using tcpdump, you can find the real IP address of a website behind a CDN by capturing and analyzing the network traffic between your computer and the website.
Here is an example of how to use tcpdump to find the real IP address of a website behind a CDN:
Open a terminal or command prompt on your computer.
Type the following command and press Enter: ``` tcpdump -i [interface] -nn ```
Replace "[interface]" with the name of the network interface you want to use to capture network traffic.
For example, if you want to capture network traffic on the "eth0" interface, you would type the following command:

``` tcpdump -i eth0 -nn ```

Open a web browser on your computer and go to the website you want to find the real IP address of.
In the terminal where tcpdump is running, look for the DNS response packets that contain the IP address of the website. The IP address of the origin server that is serving the website behind the CDN will be in the "Answer" section of the DNS response packet.




+ Another way to find the real IP address of a website behind a CDN is to use a DNS history website such as "DNS History". DNS History is a website that provides a searchable database of DNS records, including the historical DNS records of a domain. By using DNS History, you can find the real IP address of a website behind a CDN by looking up the historical DNS records of the domain.
Here is an example of how to use DNS History to find the real IP address of a website behind a CDN:
Go to the DNS History website at https://dnshistory.org/.
In the "Domain Name" field, type the name of the website you want to find the real IP address of and press Enter.
For example, if the website you want to find the real IP address of is "example.com", you would type "example.com" in the "Domain Name" field.
The DNS History website will show the historical DNS records for the domain, including the IP address of the origin server that is serving the website behind the CDN.



+ Another way to find the real IP address of a website behind a CDN is to use a technique called SSRF (Server-Side Request Forgery). SSRF is a type of web vulnerability that allows an attacker to send malicious requests from the vulnerable server to other servers or services on the network. By exploiting an SSRF vulnerability, an attacker can bypass the CDN and send requests directly to the origin server, allowing them to find the real IP address of the website.
Here is an example of how to use SSRF to find the real IP address of a website behind a CDN:
Find a web application that is vulnerable to SSRF and that is running on a server that can access the website you want to find the real IP address of.
Use the SSRF vulnerability to send a request from the vulnerable server to the website, using a specially crafted URL that includes the IP address of the origin server that is serving the website behind the CDN.
For example, if the website you want to find the real IP address of is "example.com" and the IP address of the origin server is "192.0.2.1", you could use the following URL in the SSRF request:
http://192.0.2.1/index.html
If the SSRF request is successful, the server will return the contents of the website hosted at the IP address specified in the URL. This will allow you to find the real IP address of the website behind the CDN.




+ Another way to find the real IP address of a website behind a CDN is to use a network scanning tool such as Nmap. Nmap is a powerful network scanning and security tool that can be used to discover hosts and services on a network, including the real IP addresses of websites behind a CDN.
Here is an example of how to use Nmap to find the real IP address of a website behind a CDN:
Install and open Nmap on your computer.
In Nmap, use the "Host Discovery" options to scan the network for hosts that are serving the website you want to find the real IP address of.
For example, if the website you want to find the real IP address of is "example.com", you could use the following command to scan for hosts serving the "example.com" domain:
nmap -sn -PS example.com
This command will use the "Ping Scan" (-sP) and "SYN Ping" (-PS) options to scan the network for hosts serving the "example.com" domain.
In the output of the scan, look for the IP address of the origin server that is serving the website behind the CDN. This will be the real IP address of the website.





+ Another way to find the real IP address of a website behind a CDN is to look for misconfigurations in the CDN or the website itself. Sometimes, CDN providers or website administrators may accidentally expose the real IP address of the origin server in the configuration of the CDN or the website. By looking for these misconfigurations, you may be able to find the real IP address of the website behind the CDN.
Here are some examples of common misconfigurations that can expose the real IP address of a website behind a CDN:
Incorrect DNS configuration: The CDN provider or website administrator may have accidentally configured the DNS records for the website to point directly to the origin server, instead of to the CDN. This can expose the real IP address of the origin server in the DNS records.
Unsecured or outdated web server software: The web server software running on the origin server may have vulnerabilities that can be exploited to disclose the real IP address of the server. For example, older versions of web server software may have a "server banner" feature that exposes the real IP address of the server in the HTTP response headers.
Exposed debug information: The website or the CDN may have debug information enabled that exposes the real IP address of the origin server. For example, the website may have an error page that shows the real IP address of the server in the debug information.
To find the real IP address of a website behind a CDN by looking for misconfigurations, you can use a web application scanner such as Burp Suite or a network scanner such as Nmap to scan the website and the CDN for these types of vulnerabilities and misconfigurations.




+ Another way to find the real IP address of a website behind a CDN is to use social engineering techniques. Social engineering is the use of psychological manipulation to trick people into revealing sensitive information. By using social engineering techniques, you may be able to trick the website administrator or the CDN provider into revealing the real IP address of the website behind the CDN.
Here is an example of how to use social engineering to find the real IP address of a website behind a CDN:
Find the contact information for the website administrator or the CDN provider, such as their email address or phone number.
Pretend to be a legitimate user or customer of the website, and contact the website administrator or the CDN provider.
Use social engineering techniques to trick the website administrator or the CDN provider into revealing the real IP address of the website behind the CDN.
For example, you could pretend to be having technical problems with the website and ask the website administrator for help. You could then ask the website administrator for the IP address of the website, and they may unwittingly give you the real IP address of the origin server behind the CDN.



+ Here are some other tools that can help you find the real IP address of a website behind a CDN:
1. ```Burp Suite```: Burp Suite is a web application security testing platform that can be used to scan websites and web applications for vulnerabilities and misconfigurations. By using Burp Suite, you can find the real IP address of a website behind a CDN by scanning the website and the CDN for vulnerabilities and misconfigurations that can expose the real IP address of the origin server.
1. ```SSRFmap```: SSRFmap is a tool that can be used to exploit Server-Side Request Forgery (SSRF) vulnerabilities to find the real IP address of a website behind a CDN. By using SSRFmap, you can find the real IP address of a website behind a CDN by exploiting an SSRF vulnerability on a vulnerable server that can access the website.
1. ```curl```: curl is a command-line tool that can be used to transfer data from or to a server, using various protocols. By using curl, you can find the real IP address of a website behind a CDN by sending a request to the website with the IP address of the origin server in the URL, and then looking at the response headers to find the IP address of the server.
1. ```whois```: whois is a command-line tool that can be used to look up information about domain names and IP addresses, including the registration and ownership details of a domain. By using whois, you can find the real IP address of a website behind a CDN by looking up the domain name of the website and then looking for the IP address of the origin server in the whois record.
1. ```traceroute```: traceroute is a command-line tool that can be used to trace the path of packets from your computer to a destination host, such as a website behind a CDN. By using traceroute, you can find the real IP address of a website behind a CDN by tracing the path of packets from your computer to the website and looking for the IP address of the origin server in the traceroute output
1. ```Metasploit```: Metasploit is a powerful penetration testing platform that can be used to exploit vulnerabilities and perform advanced attacks on networks and systems. By using Metasploit, you can find the real IP address of a website behind a CDN by exploiting vulnerabilities on the website or the CDN to disclose the real IP address of the origin server.
1. ```Shodan```: Shodan is a search engine for the Internet of Things (IoT) that can be used to find connected devices and systems on the Internet, including servers and websites. By using Shodan, you can find the real IP address of a website behind a CDN by searching for the domain name of the website and looking for the IP address of the origin server in the Shodan results.
1. ```ntopng```: ntopng is a network traffic monitoring and analysis tool that can be used to monitor and analyze network traffic in real-time, including the traffic to and from a website behind a CDN. By using ntopng, you can find the real IP address of a website behind a CDN by capturing and analyzing the network traffic between your computer and the website.
1. ```tcptraceroute```: tcptraceroute is a command-line tool that can be used to trace the path of TCP packets from your computer to a destination host, such as a website behind a CDN. By using tcptraceroute, you can find the real IP address of a website behind a CDN by tracing the path of TCP packets from your computer to the website and looking for the IP address of the origin server in the tcptraceroute output.
1. ```ipify```: ipify is a simple API service that can be used to get the current IP address of your computer or your internet connection. By using ipify, you can find the real IP address of a website behind a CDN by visiting the website through the CDN and then using the ipify API to get the IP address of the server that you are connected to.
1. ```Maltego```: Maltego is a powerful data mining and information gathering tool that can be used to discover and visualize hidden relationships and connections in large amounts of data. By using Maltego, you can find the real IP address of a website behind a CDN by analyzing the DNS records, network traffic, and other data related to the website to identify the real IP address of the origin server.
1. ```OpenVAS```: OpenVAS is an open-source vulnerability scanning and management platform that can be used to scan networks and systems for vulnerabilities and security risks. By using OpenVAS, you can find the real IP address of a website behind a CDN by scanning the website and the CDN for vulnerabilities and misconfigurations that can expose the real IP address of the origin server.
1. ```SecurityTrails```: SecurityTrails is a platform for cybersecurity and threat intelligence that provides access to a large database of DNS, IP, and domain data. By using SecurityTrails, you can find the real IP address of a website behind a CDN by looking up the domain name of the website and then looking for the IP address of the origin server in the SecurityTrails data.
1. ```PassiveTotal```: PassiveTotal is a threat intelligence platform that provides access to a large collection of DNS, IP, and domain data, as well as advanced tools for analyzing and visualizing this data. By using PassiveTotal, you can find the real IP address of a website behind a CDN by looking up the domain name of the website and then looking for the IP address of the origin server in the PassiveTotal data.
1. ```Recon-ng```: Recon-ng is a web reconnaissance framework that can be used to gather and organize information about a target domain, including the real IP address of a website behind a CDN. By using Recon-ng, you can find the real IP address of a website behind a CDN by using the built-in modules and tools to gather and analyze data about the website and the CDN.
