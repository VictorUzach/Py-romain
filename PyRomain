unites = {0 : " ", 1: "I" , 2 : "II" , 3 : "III" , 4 : "IV" , 5 : "V" , 6 : "VI" , 7 : "VII" , 8 : "VIII" , 9 : "IX" }
dizaines = {0 : " ", 1: "X" , 2 : "XX" , 3 : "XXX" , 4 : "XL" , 5 : "L" , 6 : "LX" , 7 : "LXX" , 8 : "LXXX" , 9 : "XC" }
centaines = {0 : " ", 1: "C" , 2 : "CC" , 3 : "CCC" , 4 : "CD" , 5 : "D" , 6 : "DC" , 7 : "DCC" , 8 : "DCCC" , 9 : "CM" }


def conversion_en_chiffres_romains () :
    x = int(input("Quel nombre veux-tu convertir en chiffres romains entre 1 et 999 ?"))
    c = int(x/100)       #On cherche le nombre des centaines du nombres demander (s'il y en a un)
    d = int((x-c*100)/10)       #On fait pareil avec le nombre des dizaine
    u = int((x-c*100-d*10))       #Puis le chiffre des unités
    print(centaines[c],dizaines[d],unites[u])

conversion_en_chiffres_romains ()
