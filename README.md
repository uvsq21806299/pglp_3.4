# pglp_3.4

1) D'après cette solution, la classe SimplePrinter n'utilise que la methode print(), donc il faut créer d'autre classe pour les autres methodes qui ne sont pas utilisés. La solution ne respecte pas ISP

2) Si on change l'interface de la méthode en 
            
         void fax(List<Document> l);
 
 L'impact que ça aura avec SimplePrinter c'est que cela ajoute juste une méthode de plus que la classe n'utilisera qui sera redéfinie, et viole les principes du ISP.
 
 
