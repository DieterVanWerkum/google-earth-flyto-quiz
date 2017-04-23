# google-earth-flyto-quiz
Only the right answer flies you to the next question!


Hi folks!

Isn't it great that interactive Google Earth quizes can now be played in a webbrowser! 

I adapted my Google Earth quiz template for use in the new Google Earth for Chrome and Android.

For now some pointers but I hope toi look into (translation from Dutch) eleborating shortly.

This will be the right place to check for updates.



*
*
* Template for Google Earth Flyto quiz by All Over The Place
* Version 1.0.1. (170421, adapted for use in the new Google Earth (for Chrome and Android)
* https://github.com/DieterVW/google-earth-flyto-quiz
* 2008-2017 Dieter van Werkum. This work is licensed under Creative Commons Attribution 4.0 International License.
* http://creativecommons.org/licenses/by/4.0/
* 
*
*
* Tips (Check https://github.com/DieterVW/google-earth-flyto-quiz for updates.)
*
* Noteer hier (bovenaan de code) van elke vraag wat het juiste antwoord is. Dan kun je door knippen en plakken hieronder de volgorde van foute en goede antwoorden afwisselen.
* 
* vraag 1: het juiste antwoord is ...............
* vraag 2: het juiste antwoord is ...............
* vraag 3: het juiste antwoord is ...............
* etc., etc.
* 
* 
* Wanneer u het aantal onjuiste antwoorden in een vraag uitbreidt, dient u verder naar beneden ook code voor een bijbehorende antwoord-balloon te voegen. Anders kapt de quiz/rondvlucht af.
* 
* In de code van de vragen kan de mogelijkheid tot 'valsspelen' worden geactiveerd. De links "sla deze vraag over" zijn momenteel onzichtbaar, want staan tussen haken.
* 
*
*
* Code (wat u minimaal weten moet)
*
* (Belangrijk: Laat <br>, <p> en <font color="#111111"> aan het begin van regels staan. Ze regelen een nette opmaak.)
*
* U kunt hieronder de tekst van vragen, antwoorden en tekstallinea's zelf veranderen. Of linken naar (kleine!) plaatjes elders op het web. 
* 
* De quiz maakt gebruik van KML 2.2. Google extensies <a href="#1;flyto"> en <a href="#1;balloon"> in de (html) description van placemarks (en folders). 
* - foutieve antwoorden worden afgehandeld door <a href="#IDvanFolder;balloon" (dus zonder flyto).
* - goede antwoorden worden afgehandeld door #IDvanPlacemark;flyto (naar de volgende placemark.
* 
* Stramien van gelinkte ID's:
* 	(wrong)answer a to question 1: linktarget #q1aF;balloon (opens balloon with question, no flyto)
* 	(wrong)answer b to question 1: linktarget #q1aF;balloon (opens balloon with question, no flyto)
* 	(correct)answer (c) to question 1: linktarget #q1ac;balloon (opens ballooon with flyto link, to placemark with the next question)
* 	etc.
* Stramien meerkeuze: q1aa=question1-answerA' (b,c,d, etc.)
* Stramien waar of niet waar: q1aT=question 1 answer 'True' (of F=false)
* 
*
* 

