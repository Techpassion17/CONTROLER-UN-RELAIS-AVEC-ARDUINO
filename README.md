# CONTROLER-UN-RELAIS-AVEC-ARDUINO
Contrôler un relais avec ARDUINO l'objectif est de pouvoir montrer comment utiliser un relais avec arduino

le transistor dans ce montage est utilisé en régime de comutation

*** lorsque nous envoyons une tension de 5V a la base du transistor c'est a dire digitalWrite(2,HIGH) le transistor deviens alors passant ainsi la bobine du relais est exité cette dernière entraîne la fermeture de l'interrupteur interne du relais et occasione l'allumage de la led.

*** lorsque nous n'envoyons aucune tension a la base du transistor c'est a dire digitalWrite( 2,LOW) le transistor est bloqué ainsi la bobine du relais n'est pas exité donc l'interrupteur du relais ne se ferme pas ainsi la led aussi ne s'allume pas. 
