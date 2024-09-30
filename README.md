# QDT-Monitoring
Ett verktyg som kontrollerar om QVD-filer är uppdaterade under dagens datum. Perfekt för användare av QDT eller liknande system som behöver övervaka filuppdateringar.

![image](https://github.com/user-attachments/assets/72991ed3-a86a-4c31-9dd6-3f3b134778fc)

## Innehållsförteckning
1. [Info](#info)
2. [Installation](#installation)
3. [Slutförd](#slutförd)

---

## Info
Automationen loopar igenom alla filer i ett valt utrymme och verifierar om filerna har uppdaterats dagens datum. Det finns även möjlighet att exkludera specifika filer från övervakningen.

---

## Installation
### Steg 1
Ladda ner JSON-filen från repositoryt och ladda upp den i din workspace.

![image](https://github.com/user-attachments/assets/52a54133-7824-4a2d-be11-0e55aae2215a)

### Steg 2
Ändra kundens namn enligt dina behov.

![image](https://github.com/user-attachments/assets/d296cb29-1df5-4955-861f-4f4154e78fe9)

### Steg 3
Välj det utrymme (SpaceID) där dina QVD-filer är lokaliserade.

![image](https://github.com/user-attachments/assets/9545743a-5cae-4294-b8f1-5089ce6813d0)

### Steg 4
Ange de filer som ska exkluderas från automationen. Dessa filer kommer att hoppas över. Använd formatet `Fil.qvd,` och separera filnamn med kommatecken. (Sista filen kan ha ett komma eller ej, detta påverkar inte resultatet.)

![image](https://github.com/user-attachments/assets/c4027489-2303-4a93-b7ce-492870e2d329)

### Steg 5
Välj hur ofta applikationen ska köras. Rekommenderar en gång om dagen.
![image](https://github.com/user-attachments/assets/25df34b3-ddee-4c86-b217-451a15668640)

### Steg 6
Konfigurera SMTP på mejlblock (2st!)
![image](https://github.com/user-attachments/assets/b528bc34-af97-486b-af17-d2616a7c5a15)



---

## Slutförd
Automationen är nu konfigurerad och klar för användning!

