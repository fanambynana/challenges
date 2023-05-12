# 1. FTP Authentification
- Démarrer le challenge
- Ouvrir le fichier ch1.pcap avec wireshark
- Filtrer les TCP
- Suivre la session avec "Request: ... "

# 2. Telnet Authentification
- Telecharger et ouvrir le fichier ch2.pcap
- Suivre le flux TCP et on obtient le mot de passe

# 3. Ethernet Trame
- Ovrir le lien sur "Démarrer le challenge"
- Copier et décoder le code hexadécimale entre "Authorization : ....." et "==" en texte
- Puis on obtient le code en base 64 et le décoder pour obtenir le mot de passe

# 4. Authentification twitter
- Ouvrir le fichier ch2.pcap
- > Hypertext Transfer Protocol
- > Authorization
- Credentials -- usertest

# 5. Bluetooth - Fichier iconnu
- Démarrer le challenge
- Ouvrir le fichier ch18.bin avec Wireshark
- > Wireless
- > équipements Bluetooth
- Concaténer l'adresse MAC en majuscule avec le nom du téléphone
- Convertir en Sha1 et on obtient le hash
