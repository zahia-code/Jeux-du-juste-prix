import random 

def justeprix():
     print("--- Jeux du juste prix ---")
     
     mystere = random.randint(1,100)
     choix = (0)

     while choix != mystere:
        try :
            choix = int(input("Devine le nombre (entre 1 et 100) : "))
      
            if choix < mystere:
               print("C'est plus !")
            elif choix > mystere:
               print("C'est moins !")
           
        except ValueError:
            print("Erreur : Tu dois taper un chiffre entier.")
     print(f"Bravo, le nombre était bien {mystere}. ")
    
justeprix()
