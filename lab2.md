1. What is the Address Resolution Protocol (ARP), and what is its role in a network?
ARP - komunikacijski protokol kojim se dobiva fizička adresa na lokalnoj mreži iz poznate mrežne adrese. Najraširenija upotreba je na Enthernetu gdje se IP adrese povezuju s MAC adresama.

2.  is a Man-in-the-Middle (MitM) attack, and how does ARP spoofing enable it?
Man-in-the-Middle attack je tip napada u kojem napadač ubaci sebe u metodu komunikacije. ARP se može iskoristiti lažiranjem ARP odgovora.
 
3. How does an attacker use ARP spoofing to intercept network traffic?
Napadač koristi lažni odgovor tako da tvrdi da je točna MAC adresa za traženu IP adresu na sustavu koji pripada dapadaču.

4. How is the cookie used to derive the encryption/decryption key?
Kod enkripcije temeljene na kolačićima, poslužitelj web stranice šifrira osjetljive podatke pomoću jedinstvenog ključa za šifriranje i zatim pohranjuje šifrirane podatke u kolačić na računalu korisnika.

5. What REST API request do you need to send to the crypto oracle the secret cookie?
GET/arp/cookie

6. How do you obtain the authentication token?
Tako da ga zahtjevamo od crypto oracle servera sa ispravnim akridetacijama(credentials).

7. How do you use the authentication token to obtain the cookie?
Potreban je kao dio zahtjeva poslužitelju.

8. What encryption mode is used to encrypt the challenge in this lab?
AES-CBC

9. What tool can you use to capture network traffic on a local network interface?
tcpdump

