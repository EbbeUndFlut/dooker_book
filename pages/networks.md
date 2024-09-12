# Netzwerken mit Docker

## Die 3 Arten von Netzwerke

**Bridge:** Alle Container, die dem selben Bridge Netzwerk angehören, und der Host können miteinander kommunizieren. Wenn man ein eigenes Bridge Network erstellt, können die Container sich über ihren Containernamen erreichen  
**Host:** Der Container teilt sich das Netzwerk mit dem Host, wir benötigen hier kein Portmapping mehr *-p 8080:8080* Der Container bekommt auch keine eigene IP Adresse  
**None:** Der Container wird komplett isoliert betrieben. Weder der Host noch andere Container können darauf zu greifen.  
