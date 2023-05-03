Download Link: https://assignmentchef.com/product/solved-cs3516-lab-assignment-2
<br>
Updates on Q3:

In the lab assignment 2, we have Q3 on page 3 as follows.

Q3. Run <em>nslookup </em>so that one of the DNS servers obtained in Question 2 is queried for the mail servers for Yahoo! mail. What is its IP address?   For example, you may run  nslookup mail.yahoo.com dns.external dns.external is the dns server you obtained from Q2.

Your query may get refused by using the external dns server.

To answer Q3, you can use some public dns server to do so.  You can find an IP list of public DNS servers from the following webpage.




<u>https://www.lifewire.com/free-and-public-dns-servers-2626062</u>




For      example,                     you      can      use      209.244.0.3, a public DNS server from Level3, and get the following results.




nslookup mail.yahoo.com 209.244.0.3

Server:  209.244.0.3

Address: 209.244.0.3#53




Non-authoritative answer:

mail.yahoo.com canonical name = login.yahoo.com. login.yahoo.com canonical name = fo-dsats.member.g02.yahoodns.net.

Name: fo-ds-ats.member.g02.yahoodns.net

Address: 98.139.21.169