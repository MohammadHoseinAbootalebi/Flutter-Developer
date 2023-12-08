# <span style="color:orange"><b>Hi Flutter</b></span>

This application is the easiest and first application that every programmer or developer programs when he/she enters the world of new programming languages. So, in this application I said hello to Flutter ;)

# <h2 id="Table_Of_Contents">**Inhaltsverzeichnis**</h2>

1. <a href="#application_properties">Anwendungseigenschaften</a>
2. <a href="#designing_part">Designteil</a>
    1. <a href="#wireframing_section">Wireframing</a> 
    2. <a href="#designing_section">Entwerfend</a>
    3. <a href="#prototyping_section">Prototyp entwickeln</a>
    4. <a href="#mockups_section">Mockups</a>
3. <a href="#programming_part">Programmierteil</a>
    1. <a href="#front_end">Front-end</a>
    2. <a href="#back_end">Back-end</a>
    3. <a href="#review_functionality">Überprüfen Sie die Funktionalität</a>

## **<p id="application_properties"><b>1. Anwendungseigenschaften</b></p>**
Die Anwendungseigenschaften sind wie folgt: <br>

- Name: **Hi Flutter**
- Zeit zum Abschluss: **3 Stunden**
- Datum des Abschlusses des Antrags: **23rd November 2023**
- Ebene: **Anfänger**

<a href="#Table_Of_Contents">[↑ Zurück ↑]</a>

## **<p id="designing_part"><b>2. Designteil</b></p>**
In diesem Abschnitt stelle ich den Designprozess vor, der zur Entstehung des „Hi Flutter“ erforderlich ist. <br>
<a href="#Table_Of_Contents">[↑ Zurück ↑]</a>

### **<p id="wireframing_section"><b>2.1 Wireframing</b></p>**
In diesem Teil stelle ich das Wireframe- oder Low-Level-Design „Hi Flutter“ vor.<br>

In der folgenden Abbildung wird das Basis-Drahtmodell der Anwendung dargestellt:<br><br>

<img src="../../Assets/Hi Flutter/Presentations/Wireframing.png" width="100%" height="100%"><br>

Wie man sieht, enthält die Anwendung zwei Hauptbildschirme:
- Der linke Bildschirm ist der erste Bildschirm, der im Hintergrund ein Bild des Flatterlogos und im Vordergrund ein Bild des Dash enthält. Unten befindet sich außerdem ein Textfeld und unterhalb des Textfelds eine CTA-Schaltfläche. Die Schaltfläche ist so konzipiert, dass sie zum rechten Bildschirm wechselt, wenn der Benutzer darauf tippt.</br></br>
- Der rechte Bildschirm ist der nächste Bildschirm, der erscheint, wenn der Benutzer auf die Schaltfläche „Call Dash“ tippt. Es wird ein Dialogfeld mit einer Schaltfläche „OK“ zum Schließen und einem Textfeld zum Anzeigen von Text im Dialogfeld angezeigt.

<a href="#Table_Of_Contents">[↑ Zurück ↑]</a>

### **<p id="designing_section"><b>2.2 Entwerfend</b></p>**
In diesem Teil wird das endgültige Design der Anwendung „Hi Flutter“ vorgestellt:<br>

The total design at one glance is like the picture below. This design was done in the Adobe XD software.[*]<br><br>

<img src="../../Assets/Hi Flutter/Presentations/Design - One Sight.png" width="100%" height="100%"><br>

Each designed screen is coming:

- First application screen [**Welcome Screen**] ↓ :<br><br><img src="../../Assets/Hi Flutter/Presentations/First Screen.png" width="100%" height="100%">

- Second application screen [**Dialog Screen**] ↓ :<br><br><img src="../../Assets/Hi Flutter/Presentations/Second Screen.png" width="100%" height="100%">

- First application screen landscape view [**Welcome Screen**] ↓ :<br><br><img src="../../Assets/Hi Flutter/Presentations/First Screen - Landscape.png" width="100%" height="100%">

- Second application screen landscape view [**Dialog Screen**] ↓ :<br><br><img src="../../Assets/Hi Flutter/Presentations/Second Screen - Landscape.png" width="100%" height="100%">

<a href="#Table_Of_Contents">[↑ Zurück ↑]</a>

### **<p id="prototyping_section"><b>2.3 Prototyping</b></p>**
In this part, I present the prototype or high-level "Hi Flutter" design.

As the functionality of this application is very simple, for its prototype, in the first application screen that is the welcome screen - whether in the portrait or landscape view - the dialog box will be shown as follows:

- Prototype of first screen [**Welcome Screen In Portrait View**] ↓ : <br><br><img src="../../Assets/Hi Flutter/Presentations/Call Dash CTA Button.png" width="100%" height="100%">

- Prototype of first screen [**Welcome Screen In Landscape View**] ↓ : <br><br><img src="../../Assets/Hi Flutter/Presentations/Call Dash CTA Button Landscape.png" width="100%" height="100%">

- Prototype of second screen [**Dialog Box Screen In Portrait View**] ↓ : <br><br><img src="../../Assets/Hi Flutter/Presentations/OK Button in the dialog box portrait.png" width="100%" height="100%">

- Prototype of second screen [**Dialog Box Screen In Landscape View**] ↓ : <br><br><img src="../../Assets/Hi Flutter/Presentations/OK Button in the dialog box landscape.png" width="100%" height="100%">

<br><a href="#Table_Of_Contents">[↑ Zurück ↑]</a>

### **<p id="mockups_section"><b>2.4 Mockups</b></p>**
In this part, I present the final results in terms of Mockups.<br><br>

<img src="../../Assets/Hi Flutter/Presentations/Mockups/Single Mockup - First Screen.png" width="100%" height="100%">

<br>

<img src="../../Assets/Hi Flutter/Presentations/Mockups/Single Mockup - Second Screen.png" width="100%" height="100%">

<br>

<video width="100%" height="100%" controls>
  <source src="../../Assets/Hi Flutter/Presentations/Mockups/Portrait Hi Flutter.mp4" type="video/mp4">
</video>

https://github.com/MohammadHoseinAbootalebi/Flutter-Developer/assets/111989636/e95f545a-39a5-4f3b-8422-c938c9ea8c9c

<br><a href="#Table_Of_Contents">[↑ Zurück ↑]</a>

## **<p id="programming_part"><b>3. Programming Part</b></p>**
In this section, I present the programming process that takes for the "Hi Flutter" to be born.<br>
<a href="#Table_Of_Contents">[↑ Zurück ↑]</a>

### **<p id="front_end"><b>3.1 Front-end</b></p>**
In this part, I present what things are there in the front for user interaction.<br>

- First Screen [**Welcome Screen**] ↓ :<br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/Front_end_First_Screen.png" width="100%" height="100%"><br><br>

- Second Screen [**Dialog Box Screen**] ↓ :<br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/Front_end_second_Screen.png" width="100%" height="100%">

<br>As shown, the application is programmed as designed, with its pictures being displayed in the previous sections.

<br><a href="#Table_Of_Contents">[↑ Zurück ↑]</a>

### **<p id="back_end"><b>3.2 Back-end</b></p>**
In this part, I present what things are there in the back for functionality to work.<br>

I will show what widgets are used in the background. The full details could be neglected because it makes reading this documentation boring.<br><br>

- **Flutter Picture** <br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/Flutter Picture.png" width="100%" height="100%"><br><br><p>As it is seen, the entire widgets are in a single "**Stack**" widget as this UI is somehow a complex one. And all of them wrapped around with a "**SingleChildScrollView**" widget for where it is needed it could be scrollable. Anyway, this Flutter picture logo is just an image widget that I designed previously in Ai.</p>

<br><br>

- **Dash Picture** <br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/Dash Picture.png" width="100%" height="100%"><br><br><p>This is an image widget too like the previous one that is positioned in the Stack widget.</p>

<br><br>

- **Bellow Dash Image Text Box** <br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/Start Big Journey Text.png" width="100%" height="100%"><br><br><p>This is just a text box containing the "Start your big journey" text.</p>

<br><br>

- **Call to Action Button** <br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/Call Dash Button.png" width="100%" height="100%"><br><br><p>This is a "**Text Button**" widget that when it is pressed, it shows a dialog box or call "**showDialog**" method used commonly in Flutter.</p>

<br><br>

- **Dialog Box Title** <br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/I recieved your Call.png" width="100%" height="100%"><br><br><p>After pressing the "**Call Dash**" button, a dialog box like this appears. It contains three different widgets. Its first one is a text box widget containing "**I received your Call!**" text.</p>

<br><br>

- **Dialog Box Content** <br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/dialog text content.png" width="100%" height="100%"><br><br><p>This is a text box too that is used as a placeholder to show some content in the dialog box.</p>

<br><br>

- **Dialog Box Button** <br><br><img src="../../Assets/Hi Flutter/Presentations/Programming Parts/OK button.png" width="100%" height="100%"><br><br><p>And in the below of the dialog box content, a button is used. After pressing, the dialog box will disappear and the first screen or welcome screen will show again.</p>

<br><a href="#Table_Of_Contents">[↑ Zurück ↑]</a>

<br>

### **<p id="review_functionality"><b>3.3 Review Functionality</b></p>**

To review the functionality of the application overall again, let's see the following video:<br><br>

<video width="100%" height="100%" controls>
  <source src="../../Assets/Hi Flutter/Presentations/Final Videos/Galaxy S Ultra - Landscape.mp4" type="video/mp4">
</video><br><br>

https://github.com/MohammadHoseinAbootalebi/Flutter-Developer/assets/111989636/56efc17f-70f0-4fcc-9bcb-30bce6caa61c

<video width="100%" height="100%" controls>
  <source src="../../Assets/Hi Flutter/Presentations/Final Videos/S Ultra - Landscape - not Portrait.mp4" type="video/mp4">
</video><br><br>

https://github.com/MohammadHoseinAbootalebi/Flutter-Developer/assets/111989636/6786c4c6-a265-4a7c-997e-ff46333fce83

<video width="100%" height="100%" controls>
  <source src="../../Assets/Hi Flutter/Presentations/Final Videos/Note 10 Lite - Both View.mp4" type="video/mp4">
</video><br>

https://github.com/MohammadHoseinAbootalebi/Flutter-Developer/assets/111989636/22fc8944-4509-406f-835f-ec647ce56bc5

<br><a href="#Table_Of_Contents">[↑ Zurück ↑]</a>