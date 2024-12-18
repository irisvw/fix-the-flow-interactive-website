
Ontwerp en maak een interactieve website voor een opdrachtgever.

De instructie vind je in: [INSTRUCTIONS.md](https://github.com/fdnd-task/fix-the-flow-interactive-website/blob/main/docs/INSTRUCTIONS.md)

# Qatar Museums: De collectie
<!-- Geef je project een titel en schrijf in één zin wat het is -->
Om de collectie weer te geven, heeft Qatar Museums een nieuwe pagina nodig. Met behulp van filters en een zoekbalk kunnen gebruikers kunstwerken zoeken en meer informatie vinden.
https://github.com/fdnd-agency/fabrique/tree/design-challenge

## Inhoudsopgave Readme

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Licentie](#licentie)

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
Ik heb drie user stories opgesteld voor de mogelijke gebruikers.

- Je bent geinteresseerd in de cultuur van Qatar. Je wilt een willekeurige selectie zien van de collectie van Qatar Museums.
- Je wilt iets specifieks opzoeken in de collectie van Qatar Museums.
- Je wilt kunst zien uit een specifieke categorie, bijvoorbeeld glaswerk.

Ik heb op basis hiervan een ontwerp bedacht dat al deze gebruikers gelukkig zou maken. Het resultaat is een slideshow. Als je op de collectie pagina beland, was het idee dat de pagina een willekeurige categorie kiest, en daar een willekeurige afbeelding voor laadt. Dit heb ik nog niet geimplementeerd.

![qatar](https://github.com/user-attachments/assets/616b4f96-5a7b-4c0b-8604-3a7e003de71b)

Op dit moment laadt de pagina telkens dezelfde afbeeldingen, uit alle categorieën. De gebruiker kan de filters selecteren, zodat de slideshow enkel afbeeldingen uit die filter weergeeft. De geselecteerde filter wordt onderstreept. Als nogmaals op de filter wordt geklikt, is het idee dat de gebruiker geleid wordt naar de pagina met alle kunstwerken van die categorie.

We hebben deze sprint gefocust op gebruikersinteractie. Ik heb user tests uitgevoerd om te bevestigen dat de feedforward en feedback duidelijk zijn.

![image](https://github.com/user-attachments/assets/a09c9d64-695b-409e-8867-8c87dc2ccc4a)![image](https://github.com/user-attachments/assets/060abf7e-3058-4785-b3f9-a32a3723e033)


Vanuit de user tests bleek dat het voor gebruikers niet duidelijk was dat ze zich op de pagina van de collectie bevonden. Ik heb simpele bewegwijzering toegevoegd zodat het duidelijker is voor de gebruiker op welke pagina zij zich bevinden.


<!-- Voeg een mooie poster visual toe 📸 -->
<img src="https://github.com/user-attachments/assets/54989352-407d-4f9a-88aa-2cf3e9d99580" height="350">
<img src="https://github.com/user-attachments/assets/bd685f5c-c03e-4365-9980-3d7200b48e6d" height="350">

<!-- Voeg een link toe naar Github Pages 🌐-->
Live link: https://irisvw.github.io/fix-the-flow-interactive-website/#

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met JS gedaan en hoe? -->
Ik heb JS gebruikt om de slideshow te bouwen. De artObjectsList wordt doorlopen en gesorteerd in de techniqueLists. Wanneer op een filter wordt geklikt, worden de afbeeldingen uit die categorie geladen. Er wordt hiervoor een willekeurig nummer gegenereerd tussen 0 en de lengte van de de lijst - de afbeelding die op die positie staat verschijnt als eerste.

## Bronnen

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

