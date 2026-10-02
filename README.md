# TP-2-Du-texte-au-vecteur-comprendre-la-logique-de-la-repr-sentation-textuelle-
# Étape 1 :
  # Partie 5 — Représentation Bag of Words
          Questions :

        Que représente chaque colonne de la matrice ?
        
            Un mot de vocabulaire , la valeur indique combient de fois le mot apparue .
          
        Quelles sont les limites du modèle Bag of Words ?
            
            Ne capture pas l'ordre et le sens .
            
        Que perd-on en supprimant l’ordre des mots ?
        
            On perd le contexte et le sens de la phrases .
        
  # Partie 6 — Représentation TF-IDF
        Questions :
        
            Quelle est la différence principale entre BoW et TF-IDF ? 
                
                le BoW compte seulement les occurrences des mots. Le TF-IDF pondère ce comptage
                
            Pourquoi les mots très fréquents ont-ils souvent un poids faible ? 
                
                Parce qu'un mot présent dans presque tous les documents ne permet pas de les distinguer. Son IDF est faible, donc son poids total aussi.
                
            Donnez un exemple concret où TF-IDF serait plus utile que BoW. 
            
                Dans un moteur de recherche ou un classement d'articles : les mots comme « le » ou « est » sont partout, alors qu'un mot comme « football » indique le sujet. Le TF-IDF met en valeur « football » et rend la recherche plus précise que le BoW.

  
