@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@ 
Configuration requise pour OpenSim Manager Web (OSMW):
	--  Apache ou xampp ou wampp ou ngnix / Mysql 
Fonctionnement:
	-- OSMW envoi des commandes au simulateur via Remote Admin 
	-- Certains fichiers doivent avoir les droits 777 pour pouvoir etre modifier par OSMW (LINUX)
	
	-- ATTENTION aux droits d'acc�s aux fichiers et le format des donn�es saisie dans vos fichiers INI 
		ex: pour remote admin pas de guillemt
		
		--> R�gions.ini (droits �criture) / OpensimDefaults.ini , etc.. qui doivent etre accessible
Pour Windows:
------------
		--> pas de soucis
Pour Linux:
------------
		--> ATTENTION aux droits d'ecritures
		
Gestion des Utilisateurs:
	=> 5 Niveaux d'acc�s sont autoris�s
	-- Administrateurs 
	-- Gestionnaires de sauvegardes
	-- Invit�s / Compte priv� par moteur
	-- 1 compte root (super admin)
	
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

******************************************
********* Suivi de versions **********
******************************************
-------------------------------------------------------
*** V 5.5 ***
/* NEWS 2015 by Nino85 Whitman */
-- Cleanup Code
-- Fix bugs


-------------------------------------------------------
*** V 5.0 ***
/* NEWS 2015 by djphil */
-- Cleanup Code
-- Fix bugs
-- Add Themes
-- Add bootstrap
-- Add Multilanguage
-- Add Google Recaptcha v2.0
-- Add Navbar
-- Add more actions, options, infos, ...
And more ...
-------------------------------------------------------

-------------------------------------------------------
*** V 4 Beta *** En cours
-- Mise � jours des SESSION
-- Systeme d'installation int�gr�s **
-- ...
-------------------------------------------------------
*** V 3.2 Final ***
-- Gestion des sauvegardes de la config des moteurs Opensim et pour chaque sim
-- Transfert des fichiers de sauvagardes vers un serveur FTP exterieur
-- Detection des fichiers de config moteurs
-------------------------------------------------------
*** V 3.0 *** MISE A JOUR MAJEUR ***
-- OSMW � sa propre base de donn�e *** Nouveaut�
-- Les Fichiers de config , conf moteurs et users sont en BDD ( prb de s�curit� !)
-- Compte Utilisateur filtr� au niveau des moteurs (choix du moteur) *** Nouveaut�
-- Verifier/ Modifier/ configurer vos INIs, opensim, grid, ... *** Nouveaut�
-- Connectivit� AdmOSMW (Referencement sur le site Fgagod.net) 
-------------------------------------------------------
*** V 2.0 ***
-- Optimisations du code
-------------------------------------------------------
*** V 1.1 ***
-- Refonte complete de l'interface
-- Syst�me d'installation simplifi�
-- Gestion des moteurs OpenSim, des utilisateurs et de la config en .INI
-- ...
--------------------------------------------------------
*** V 1.0 ***
-- Ajout de la gestion multi-Utilisateurs dans OSMW
--------------------------------------------------------
*** V0.9.11 ***
-- Authentification multi-users via fichier texte  (pas encore int�grer � OSMW)
--------------------------------------------------------
*** V0.7.11 ***
-- Ajouts de Fonctionnalt�es;
	-- Cartographie ajout�
	-- TOUS demarrer et arreter d'une seule fois
	-- Une serie de tests pour voir si tous fonctionne bien
	-- Ce fichier LOL
-- Optimisations du code
--------------------------------------------------------
*** V0.6.11 ***
-- Premiere version de OSWebManager