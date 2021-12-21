**** PROJET SITE POUR AGENCE DE VOYAGE **** 

Nous nous sommes mis dans la peau d'une agence de voyage 
Ensuite développe le site web partant de zéro en utilisant uniquement du HTML et du CSS


*** CONTENU DU SITE

    ** Une page HTML "index.html"

    ** Une page CSS "styles.css"

    ** Un dossier Images(06 images au total)
	- Une grosse image en Hero
	- Deux images sur la partie bloc 
	- Trois petites icônes 



*** ARCHITECTURE DU SITE - SQUELETTE

    ** Une Entête : La balise  <Header> </Header> 


    ** Trois Sections Unique: La balise  <Section id=nom-unique> </Section > avec des attributs Id
	- Section Hero : l'image principale du site  
			<Sections id=main-image> </Section> 
			
	- Section Steps : Les différentes étapes du voyage (contenant les 03 icônes) 
			<Sections id=steps> </Section> 

	- Section Possibilités : Contenant les Articles (chacun utilisant un bloc) 
			 <Sections id=possibilities> </Section> 
			

	- Section Contact : Contenant le formulaire de contact 
			 <Sections id=contact> </Section>


    ** Un Footer : La balise  <Footer> </Footer> 





Utilisation conteneur invisible pour centrer tout le contenu de la page grace :
- Balises div :  <div> </div>
- Attribut class : <div> class ="wrapper"</div> 





** STYLES GENARALE DU SITE
/* Les selecteur d'ordre générale sur l'intégralité du site 

1. Tout
supprimer pour tous éléments les marges externes et internes 
Ulilisation du selecteur " * "   

2. Polices - #styles  
Utiliser dans toute la page arial en police et taille générale 
Utilisation du selecteur " body "  et proprité font-family et font size


2. Tous les liens de la page 
Utilisation du selecteur " a " 
et des proprités         "text-décoration: none"
                         "coleur: 444"

3. Conteneur - #wrapper 
Conteneur invisible qui contient tous les contenues des différentes parties 
avec des marges externes auto et espacer un peu les marges internes pour ne 
pas coller le texte des traits
Utilisation du selecteur ".class"

4. Titres
Uiliser la meme couleur pour tous les titres 
Utilisation des selecteurs titres " h1, h2, h3, h4 "

5. Point sur logo
Mettre en orange pour l'élement point dans la class avec #attribut="orange"
Utilisation du selecteur " .attribut "


6. Tous Listes désordonnés
Ne pas afficher de point sur toutes nos listes désordonnés
Utilisation du selecteur " ul "  
et la  propriété         "liste style : none "" 



7. Logo Header sous forme de titre 
Faire floater à gauche gràce à la propriété float
Utilisation du selecteur " header nav" 
et la propriété          "float: left"



8. Le menu de navigation
Faire floater à droite gràce à la propriété float avec une marges externes partant du haut
Utilisation du selecteur " header nav" 
et la propriété          "float: right"
                         "margin-top :50px "       

9. Style listes désordonnés du Hearder 
Afficher toutes les listes du titre situé dans le header sur la même ligne et
les espacer chacun des éléments de la liste graces à la propriété display
et faire faire floatter chacun de ces éléments dans leur container partant de la gauche
Utilisation du selecteur " header nav ul li "  
et la proprité           "display: inline-block"
                         "float: left"

10. Texte lien Titres
Mettre le texte des liens qui se trouvent sur le menu (nav) en majuscule
Utilisation du selecteur " header nav ul li a "
et la propriété          "text-transform:  upper-case"  
                         "font-weight :bold "
                         "margin-right : 20px"


11. Police tous les titres de niveau 4

h4
{
    font-size: 24px;
    color: #444;
}

12. Police de tous paragraphes
Hauteur de ligne de 20px
Couleur légèrement plus clair	
p
{
    line-height: 20px;
    color: #777;
}

*/


