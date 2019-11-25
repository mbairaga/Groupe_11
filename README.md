class Gestionnaire:
    def Emprunt(self,Em):
        self.Emprunt=float(Em)
    def Gerecompte(self,Gcom):
        self.Gerecompte=float(Gcom)
    def Gsetionnaire(self,Emprunt,Gerecompte):
        if(Emprunt==0):
            print("Le client n'a rien emprunté = !!",self.UnEmprunt)
        else:
            print("Le client a une dette = !!",self.prêt)
    def getEm(self):
        return self.Emprunt
    def getGcom(self):
        return self.Gerecompte
    def add (self,Ajouter):
        self.Compte += Ajouter
        print("Le client ajouté est:".format(self.Emprunt))
        return self.Em
    def sub (self,Supprimer):
        self.Compte -= Supprimer
        print("Le client supprimé est:".format(self.Compte))
        return self.Em
    def mod (self,Modifier):
        self.Compte += Modifier
        print("Le client modifié est:".format(self.Gcom))
        return self.Gcom
    def take (self,Enregistrer):
        self.Compte += Enregistrer
        print("Le client enregistré est:".format(self.Compte))
ph=''
num=0

while ph != 5:
    print("\tMAIN MENU")
    print("\t1. AJOUTER CLIENT*")
    print("\t2. SUPPRIMER CLIENT*")
    print("\t3. MODIFIER CLIENT*")
    print("\t4. ENREGISTRER CLIENT*")
    print("\t5. EXIT*")
    print("\tSelect Your Option (1-5) ")
    
    ph=input()
