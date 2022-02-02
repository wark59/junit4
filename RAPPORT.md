# Rendu projet GL

## Binome
- Louis DELOFFRE
- Sabrina KERNOUF

# 1. Présentation globale JUNIT4

## 1.1.  Utilité du projet
- Junit est un framework opensource pour JAVA. Cet outil aide au developpement et à l'exécution de tests unitaires. Depuis Java 5, d'importantes évolutions ont été apportées à JUnit. Les dernières versions de JUnit ont donc changé de numéro majeur de version pour passer de JUnit 3.x à JUnit 4.x.
    * Le but de ce logiciel est d'automatiser les tests .
- Les fonctionnalités proposées par Junit sont : 
* La création d'instance de classe et de tout autre objet nécessaire aux tests.
* Produire un appel des méthodes à tester avec les paramètres nécessaires.
* Lever une exception en cas d'échec de la comparaison entre le résultat obtenu et le résultat attendu. 

- Pour mener à bien le lancement du projet, il existe plusieurs façon :
    * Compiler les classes utilisées par les tests (terminal) 
        
        ```java
         javac <nomDeClasse>.java 
        ```

    * Compiler les classes de test (terminal)
        ```java
        javac -cp .:junit-4.<version>.jar:hamcrest-core-1.3.jar <nomDeClasseTest>.java (pour macOs/Linux)
        javac -cp .;junit-4.<version>.jar;hamcrest-core-1.3.jar <nomDeClasseTest>.java (pour window)
        ```
    * Directement avec un IDE tel que Eclipse ou IntelliJ par le bouton prévu à cet effet.
    {Mettre une photo de JUNIT de eclipse}terminal
    * Par maven (projet préalablement sous maven)
        * mvn clean (si projet déjà compilé)
        * mvn install
        * mvn test

- Les sorties du logiciel : 
    * L'exécution global de tout les tests avec son nombre :
        * On distingue : 
            * Test Failure
            * Test Errors
            * Test Skipped
    ```
    Tests run: 1108, Failures: 0, Errors: 0, Skipped: 5
    ```

## 1.2. Description du projet

- Le README est présent et fournis plusieurs topics : 
    * Un wiki <https://github.com/junit-team/junit4/wiki> 


# 2. Historique du logiciel

## Analyse du git 

L'équipe est composées de 4 développeurs et le dépôt de plus de 150 contributeurs.

On constate que le dépôt git a été créé le 03 decembre 2001, mais les commits conséquents n'ont été réalisés qu'en mars 2006.
