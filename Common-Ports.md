Well known ports 0-1023

Registered ports 1024 - 49151

Private or Dynamic ports 49,152 - 65,535



20 - [TCP] FTP File Transfer Protocol FTP (Data)

21 [TCP] File transfer prtocol FTP (control)

22 [TCP] Secure Shell SSH

23 [Telnet] Telecommunication Network

25 [TCP] Simple Mail Transfer Prtocol (SMTP)

53 [UDP/TCP] Domain Name Service (DNS)

67 [UDP] Dynamic Host Configuration Protocol (DHCP) - Server

68 [UDP] Dynamic Host Configuration Protocol (DHCP) - Client

69 [UDP] Trvial File Transfer Protocol (TFTP)

80 [TCP] Hypertext Transfer Protocol (HTTP)

110 [TCP] Post Office Protocol version 3 (POP3)

135 [UDP/TCP] Microsoft EPMAP Microsoft EPMAP (End Point Mapper), also known as DCE/RPC Locator service, used to remotely manage services including DHCP server, DNS server, and WINS. Also used by DCOM

137 NetBIOS-ns TCP UDP NetBios Name Servicc used for name registration and resolution 

UDP = User Datagram Protocol 
TCP = Transmission Control Protocol
\

143 [TCP] Internet Message Access Protocol (IMAP)

161 [UDP] Simple Network Management Protocol (SNMP)

443 [TCP] Hypertext Transfer Protocol Secure (HTTPS)

Some applications may use both TCP and UDP. For example, DNS uses UDP when clients send requests to a DNS server. However, communication between two DNS servers always uses TCP.

netstat protocol

![Alt text](https://ccna-200-301.online/wp-content/uploads/2020/04/Socket-Pairs.png)
