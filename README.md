✅ validated 100% ✅

Pour tester le programme:

-Lancer le programme suivi, en argument, du port choisit.
-Ouvrir au moins deux autres fenetres de terminal et saisir sur chacunes "nc localhost <numero de port>"
-Apres avoir connecte le premier terminal, lorsaue vous connectez d'autres terminaux il doit y avoir le message "server: client x just arrived\n" sur les terminaux deja connectes.
-Pour l'envoi du message d'un client il faut qu'il y ait le message "client 'x': <votre message>" sur les autres terminaux. Testez egalement en copiant tout votre fichier et en le collant pour l'envoyer en message. Il doit etre retourne de la meme maniere.
-Lorsqu'un des clients se deconnecte de nc, les autres doivent recevoir le message "server: client 'x' just left\n".
