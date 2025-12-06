# <img width="23" src="https://upload.wikimedia.org/wikipedia/en/thumb/4/43/Feed-icon.svg/1200px-Feed-icon.svg.png"> ETFBL-Oglasi-RSS 
<a href="https://github.com/rss-bridge/rss-bridge">RSS-Bridge</a> je PHP web aplikacija za kreiranje RSS feed-ova za sajtove koji ih ne podržavaju.
ETFBL-Oglasi-RSS sadrži bridge etfblBridge.php koji služi za dohvatanje oglasa sa sajta Elektrotehničkog fakulteta u Banjoj Luci.

Da bi se ovo podesilo potrebno je u RSS-Bridge direktorijum dodati fajl etfblBridge.php u pod-direktorijum ```bridges```. Takođe ako ste podešavali da vam nisu svi RSS-Bridge-ovi omogućeni, potrebno je u fajl whitelist.txt dodati ```etfbl```.

<img width="818" height="613" alt="image" src="https://github.com/user-attachments/assets/a1e258d9-7231-4efc-a6b0-940da3e07dbc" />

Omogućeno je filtriranje po sekciji oglasa sa sajta:

<img width="254" height="335" alt="image" src="https://github.com/user-attachments/assets/d3f8af93-18d7-45bc-92d8-945ed5120225" />

Rezultat:

<img width="822" height="614" alt="image" src="https://github.com/user-attachments/assets/2658ea56-59d5-4ea9-8f78-ab4c0df6ee07" />

Primjer u programu <a href="https://github.com/newsboat/newsboat">Newsboat</a>:

<img width="462" height="47" alt="image" src="https://github.com/user-attachments/assets/cd5c58d9-dd1b-4508-b2a4-a1807d9903c2" />

<br>
<img width="898" height="283" alt="image" src="https://github.com/user-attachments/assets/59ffc5cb-e14d-4629-a54a-525cc0c8bbc6" />

<br>
<img width="1181" height="291" alt="image" src="https://github.com/user-attachments/assets/6c09e301-cb82-4cd7-accf-1a721995e624" />
<br>
Ako nemate svoju instancu RSS-Brdige, a zeljeli biste koristiti ovaj RSS feed fetcher, javite se na mejl: luka@lukazeljko.xyz
