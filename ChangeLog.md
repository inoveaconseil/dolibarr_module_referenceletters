# Change Log
All notable changes to this project will be documented in this file.

# UNRELEASED

NEW : Add substitution in agefodd to be able to use preta firstname, lastname and soc *15/02/2022*

## Version 2.9 - 14/06/2021

- FIX : unlink docedit from core odf lib to prevent html conversion to odt *23/02/2022* - 2.9.7
- FIX : Fix selection refletters default model *17/02/2022* - 2.9.7
- FIX : Compatibility V15 : token CSRF on model header and footer form *20/12/2021* - 2.9.6
- FIX : Affichage sur des documents généré docedit qui ne se faisait pas a cause de mise en forme <strong> - *13/12/2021* - 2.9.5
- FIX : In v14, select_salesrepresentatives uses -1 as empty value, sql filters adjusted accordingly *08/09/2021* - 2.9.4 
- FIX : Change default rights to 0 *01/07/2021* - 2.9.3
- FIX : Compatibility V13 *17/05/2021* - 2.9.2
- FIX - Compatibility V14 : Edit the descriptor: family - *2021-06-10* - 2.9.1
- NEW : TK2003-0572 - Qualiopi Référents Ajouter les tags DocEdit qui permettent d'y avoir acces *04/06/2021* - 2.9

## Version 2.8 - 14/04/2021

-FIX : Remove dead links *14/04/2021* - 2.8.1
-NEW : Dolibarr V13 Box compatibility *02/04/2021* - 2.8.0

## Version 2.7 - 26/03/2021

-FIX : compatibity with Dolibarr V12 (supplier_order model path changed from "core/modules/supplier_order/pdf" to "core/modules/supplier_order/doc")
-FIX : Ajout tags formation_nb_place, formation_type_public, formation_moyens_pedagogique et formation_sanction + gestion tags extrafields multiselect - 2.7.2
-FIX : Generate "Fiche Pedago" custom for an agefodd session - 2.7.1

-NEW : Add idprof1 and idprof2 tag helper

# Version 2.0 - 06/04/2017

-FIX : Preselect model on documents if default - *09/02/2022* - 2.6.6
-FIX : Specify the condition that allows the use of agefodd substitution keys only in the case of an agefodd pdf *30/06/2021* - 2.6.5
-NEW : Add mass generation for invoice model letters
-FIX : V13 compatibility add newToken to some triggers links [2021-03-03]

## 1.9 - 14/11/2016

-NEW : Only for 4.0

***** ChangeLog for 1.8 compared to 1.7 *****
-FIX : Add customer order letters

***** ChangeLog for 1.7 compared to 1.5 *****
-FIX : PHP warining for PHP 7 and dolibarr 4.0

***** ChangeLog for 1.5 compared to 1.3 *****
-NEW : Admin option to create calendar event on each letter creation
-NEW : Admin option to copy generated letters as attachement of event
-NEW : Admin option to select label type of event 
-NEW : Admin option to output in PDF ref end title of letters
-NEW : Add option to output in PDF ref end title of letters on letter création
-NEW : Add background PDF in models 
-NEW : Add read only chapter option (cannot be seen/modified during letter creation)
-NEW : Add new tags : title, ref, model title of current letter
-NEW : Letters list with filter


***** ChangeLog for 1.3 compared to 1.2 *****
-NEW : Review french/english/spanish translation
-NEW : Add french/english/spanish documentation

***** ChangeLog for 1.2 compared to 1.1 *****
-NEW : Add break page option without repeat head
-FIX : tag type {cust_...} on contact letter works 

***** ChangeLog for 1.0 compared to 1.1 *****
-FIX : Cannot create models without title 

***** ChangeLog for 0.9 compared to 1.0 *****
-NEW : Add break page option
-FIX : Contact models output a contact adress
