<p align="center">
<img width="419" alt="image" src="https://github.com/cjasper1991/Command-Line-Prompts-Pt.2/assets/126079527/827972b4-afb5-4b7f-bedd-c9d359903e76">

</p>





<h2>Environments and Technologies Used</h2>

- Command Prompt

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)



<h2>Command Prompts Pt.2 </h2>

nslookup -type=ns example.com
<p>
<img width="479" alt="image" src="https://github.com/cjasper1991/Command-Line-Prompts-Pt.2/assets/126079527/9ad1a9ec-afe1-4cf0-9cd8-5ad9b39c61f2">

</p>
<p>
Used to find the name of server domain.
</p>
<br />

nslookup -type=soa example.com
<p>
<img width="493" alt="image" src="https://github.com/cjasper1991/Command-Line-Prompts-Pt.2/assets/126079527/bdb39e54-7763-411f-bd9b-ad059437b9ad">

Used to query the SOA record of domain, (SOA a Start of Authority. Every domain must have a Start of Authority record.)
</p>
<br />

nslookup -type=mx example.com
<p>
<img width="464" alt="image" src="https://github.com/cjasper1991/Command-Line-Prompts-Pt.2/assets/126079527/9d9e1776-9f6d-44d5-80fa-47b7754dedf7">

</p>
<p>
Used to find the MX records responsible for the email exchange.
</p>
<br />

nslookup -type=any example.com
<p>
<img width="722" alt="image" src="https://github.com/cjasper1991/Command-Line-Prompts-Pt.2/assets/126079527/550cb74d-d544-411d-9f58-b2578a90a80a">

</p>
<p>
Used to find all of the available DNS records of a domain.
</p>
<br />

nslookup 10.20.30.40
<p>
<img width="782" alt="image" src="https://github.com/cjasper1991/Command-Line-Prompts-Pt.2/assets/126079527/82893d77-013f-4968-91ad-b497e55327b9">

</p>
<p>
Used to check the reverse DNS lookup.
</p>
<br />

Tracert example.com
<p>
<img width="812" alt="image" src="https://github.com/cjasper1991/Command-Line-Prompts-Pt.2/assets/126079527/4418dcfa-ef88-4a87-9331-6e67f2bd73ab">

</p>
Used to display the number of routers on the path to the destination hosts.
</p>
<br />

netstat
<p>
<img width="520" alt="image" src="https://github.com/cjasper1991/Command-Line-Prompts-Pt.2/assets/126079527/77e8262e-52ed-4819-be5a-0e83d5a0dc9c">

</p>
<p>
Lists statistics about the network connection, including the IP addresses of active conncections.
</p>
<br />

netstat -a
<p>
<img width="503" alt="image" src="https://github.com/cjasper1991/Command-Line-Prompts-Pt.2/assets/126079527/b606091d-d460-4136-9980-34c87d513956">

</p>
Lists statistics about all active connections and the ports the computer is listening on.
</p>
<br />

netstat -b
<p>
<img width="419" alt="image" src="https://github.com/cjasper1991/Command-Line-Prompts-Pt.2/assets/126079527/9cbdceb8-79d4-4000-91fd-ad055da09fc0">

</p>
<p>
Lists programs that are using the connection and is useful for finding malware that might be using the network.
</p>
<br />

nbtstat
<p>
<img width="511" alt="image" src="https://github.com/cjasper1991/Command-Line-Prompts-Pt.2/assets/126079527/8ea9a34a-4ccb-4c3a-83c6-cefd6f82d5f0">

</p>
Used to display statistics about the NetBT (NetBIOS over TCP/IP) protocol
</p>
<br />
