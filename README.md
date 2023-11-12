# A mettre dans le meme fichier que FT_PRINTF
## POUR TESTER:
Compiler avec `gcc *.c; clear` (clear juste apres pour ditch les warning).  
Avec aucun ARGV == tous les tests.   
Avec ARGV = pas tous les tests (attention que en lowercase)  
Exemple : ./a.out pci (pointeur, char, integer)  
Il suffit juste de lire le cmd et comparer User, Expected et Diff.
