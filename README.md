# security-plus-notes
security-plus-notes

## Certificates
- A CSR (certificate signing request) is used when a new, or renewed, certificate is required for a web server. It is submitted to the company that sells the SSL certificates (such as VeriSign). 



## Virus , Work , Trojan 
- A virus is designed to spread from one file to another file on an individual computer. It is not designed to automatically spread from one system to another; that would be a worm.
- A Trojan is malicious code that appears to do something legitimate but does something illegitimate outside the view of the user.


## Protocol Analyzer 
A protocol analyzer will capture packets and timestamp each one. This tells you exactly what type of packets were captured and when. If the timestamps correspond to the network activity spikes, you know you have a match for the time. By digging into the packets with a protocol analyzer, you can find out exactly what type of traffic is causing the activity. 




## Encryption
- The Data Encryption Standard (DES) is an older type of block cipher selected by the U.S. federal government back in the 1970s as its encryption standard. 



- AES is the successor to DES/3DES and is another symmetric key encryption standard composed of three different versions of block ciphers: AES-128, AES-192, and AES-256. Actually, each of these has the same 128-bit cipher block size, but the key sizes for each are 128-bit, 192-bit, and 256-bit, respectively.

- The RSA encryption protocol is an asymmetric algorithm used for the key exchange during secure web sessions. Other options for key exchange include Diffie-Hellman and elliptic curve, with or without ephemeral properties.

- 512-bit RSA keys have proven to be breakable over a decade ago; however, 1024-bit keys are currently considered unbreakable by most known technologies, but RSA still recommends using the longer 2048-bit key, which should deter even the most powerful super hackers. It is important to note that asymmetric algorithm keys need to be much larger than their symmetric key counterparts to be as effective. For example, a 128-bit symmetric key is essentially equal to a 2304-bit asymmetric key in strength.

## Attacks
- The IV (initialization vector) attack is when an attacker deciphers the fixed-size input at the beginning of each WEP or WPA packet. WEP is much more susceptible. To avoid the attack, use WPA2. 
- An evil twin is a rogue access point that is controlled by an attacker. It has the same name and configuration as one of the legitimate WAPs in an organization.
- A replay attack is a network attack in which data packets are repeated or delayed by an outside attacker. 

- Signatures are the patterns that an **IDS** looks for when detecting attacks. 
- Zero Day Attack: A completely unknown exploit found in the software that neither the manufacturer or client knew existed. This is often performed by a black hat attacker. The best way to prevent this attack is to keep updating your system and patching when needed.  Also subscribing to other IT/Cybersecurity news outlets will help you stay up to date on news relating to Zero Day incidents.

## Authentication
- Radius
- Diameter
- LDAP 
- Kerberos 


## Hashing 
- A **collision** occurs when a hashing algorithm creates the same hash from two different messages.


## Hashing vs encryption
- Encryption can be reversed with password / keys
- Hashes are one way operations. Although you can use rainbow tables to find existing hashes and crack passwords
