# COMP-S13-4-Java-5-Hubernate
Création d'un projet Hibernet Maven
1. New Project > Maven > Web Application > MaSuperApplicationTropGenial
    * Next > Finish (Attendre les téléchargements)
2. Créer Hibernate > Hibernate Config Wizard
    * File Name hibernate.cfg(.xml) à ne pas changer
    * Folder src/main/ressources
    * Next
    * Database Connection > Charger ma base MySQL
    * Database Dialect : Vérifier si OK
    * Finish
3. Créer Hibernate > HibernateUtil.Java
    * Class Name : NewHibernateUtil
    * Package : Sélectionner mon Main Package
4. Créer Hibernate > Hibernate Reverse Engineering Wizard
    * Name File : hibernate.reveng
    * Folder : src/main/resources
    * Next
    * Sélectionner mes tables
    * Finish
5. Créer Hibernate > Hibernate Mapping Files and POJOS from DB
    * Vérifier Hib Configuration File and hib Reverse Eng File
    * Cocher JDK 5 Language Features
    * Finish