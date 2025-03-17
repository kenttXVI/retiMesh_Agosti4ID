# retiMesh_BT
Approfondimenti riguardanti reti mesh - Quarta Telecomunicazioni 2025
1. **Algoritmi di Routing**
   - Routing statico - Dijkstra
   - Routing dinamico - Bellman Ford

2. **Sicurezza Reti**
   - Assicurare che non ci siano nodi malevoli, implementazione di meccanismi di 'fiducia' fra nodi basata su una reputazione
   - Suddivisione logica del traffico di dati
   - Autenticazione dei nodi prima che questo faccia parte della rete
   - Implementazione di protocolli relativi alla sicurezza:
      - IEEE 802.11s (sicurezza reti mesh di tipo wireless)
      - WPA3-Mesh (sicurezza reti mesh esclusivamente di tipo WIFI)
      - DTLS (sicurezza per comunicazioni mesh di tipo IoT)
      - Zero-trust (architettura che fa eseguire l'autenticazione ad ogni elemento che vole entrare nella rete)

3. **Ottimizzazione Energia**
   - Più nodi portano a più archi che portano a loro volta ad una larghezza di banda minore, il che a sua volta porta ad una lentezza nell'invio di dati. 
   - Sono quindi presenti più modi per garantire una larghezza di banda necessaria dal contesto in cui la rete è applicata:
     - Definire un numero massimo di nodi supportati dalla rete
     - Utilizzare una rete mesh non completa (Partial-Mesh) che implementa un numero minore di archi (rispetto ad una Full-Mesh)
