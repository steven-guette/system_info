# <span style="color: darkorange;">system_info</span>

***<span style="color: #9683EC;">system_info permet d'avoir un visuel rapide sur différentes informations du système sur lequel il se trouve.</span>***

## <span style="color: orange;">Automatiser l'exécution lors de l'ouverture d'un terminal ou une connexion SSH</span>

Commencez par télécharger le dépôt puis déplacez-vous à l'intérieur de celui-ci.
``` Bash
git clone https://github.com/steven-guette/system_info.git
cd system_info
```


Copiez ou déplacez ensuite le fichier **system-info** dans le répertoire de votre choix.
``` Bash
# Copier le fichier.
cp -v system-info répertoire/de/mon/choix

# Décplacer le fichier.
mv -v system-info répertoire/de/mon/choix
```

Ouvrez ensuite votre fichier .bashrc **(** *<span style="color: #9683EC;">Ou autre selon le shell que vous utilisez</span>* **)** à l'aide d'un editeur de texte.
``` Bash
nano ~/.bashrc
```

Ajoutez à la fin du fichier la ligne suivante en indiquant le chemin réel vers le fichier **system-info**.
``` Bash
bash chemin/vers/system-info
```

Sauvegardez et sortez de votre éditeur de texte, puis mettez à jour votre fichier .bashrc **(** *<span style="color: #9683EC;">Ou autre encore une fois</span>* **)**.
``` Bash
source ~/.bashrc
```

Si vous avez respecté chaque étape de la configuration, **system-info** devrait s'exécuter à l'intérieur de votre terminal.
Il s'exécutera désormais à chaque ouverture d'un nouveau terminal, ou si vous établissez une connexion entrante SSH vers le(s) poste(s) sur lequel il est configuré. 