# anubi-signatures
In this repo signatures used by Anubi project are kept. 

These are the result of IOC extraction from my personal MISP instance using the following open source feeds:
1. CIRCL OSINT [Feed](https://www.circl.lu/doc/misp/feed-osint)
2. The Botvrij.eu [Data](https://www.botvrij.eu/data/feed-osint)
3. Malware Bazaar [Feed](https://bazaar.abuse.ch/downloads/misp/)
4. dan.me.uk [node list](https://www.dan.me.uk/torlist/?full)
5. URLHaus [Feed](https://urlhaus.abuse.ch/downloads/misp/)
6. Threatfox [Feed](https://threatfox.abuse.ch/downloads/misp/)

Yara rules are used from the sources listed below:
1. Florian Roth Neo23x0 [signature-base repository](https://github.com/Neo23x0/signature-base)
2. Yara-Rules [rules repository](https://github.com/Yara-Rules/rules)
3. Malpedia [rules repository](https://github.com/malpedia/signator-rules)
4. Elastic [rules repository](https://github.com/elastic/protections-artifacts)
