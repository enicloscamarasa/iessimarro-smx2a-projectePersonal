# **_Projecte Intermodular_**
Repositori Github per al projecte Intermodular de 2n SMX

Utilitzant **GitHub Projects**, pots organitzar fàcilment els projectes dividint les tasques, assignant-les a membres del grup, i fer seguiment de l’estat en temps real. Això millora la **col·laboració** i la **visibilitat** de l'equip en cada fase del projecte.

## **1. Crear un repositori i habilitar GitHub Projects**

### **Pas 1.1: Crear un repositori al teu compte**

1. Ves a [GitHub](https://github.com) i inicia sessió amb el teu compte.

2. Fes clic a **\+** (a dalt a la dreta) i selecciona **"New repository"**.

3. Nom del repositori, visibilitat (públic o privat), i descripció.

4. Fes clic a **Create repository**.
   
5. Dona-li un nom, per exemple _Projecte Intermodular 2smxA_

### **Pas 1.2: Crear un projecte amb GitHub Projects**

Github Projects és una eina de gestió de tasques que permet organitzar, classificar i prioritzar les tasques d'un projecte relacionades en un repositori.

1. A la barra lateral del repositori, selecciona la pestanya **Projects**.

2. Fes clic a **"Create a project"**.

3. Posa-li un nom al teu projecte, per exemple: **"Gestió de tasques per al projecte X"**.

4. Selecciona **Project board** (el tauler) que vols utilitzar:  
    - **"Kanban"** és el més comú (mètode visual i fàcil de seguir per a tasques).

   ---

## **2. Crear i organitzar el tauler de gestió (_Project Board_)**

### **Pas 2.1: Definir les columnes**

Un tauler de **Kanban** en GitHub es compon de **columnes**. Cada columna pot representar un **estat** del projecte o una **fase** de les tasques.  
Les columnes més comunes són:

* **Backlog**: Tasques per fer.

* **To Do**: Tasques assignades però no començades.

* **In Progress**: Tasques que s'estan fent.

* **Review**: Tasques en revisió.

* **Done**: Tasques finalitzades.

Per crear o editar columnes:

1. Fes clic a **"Add column"** per crear una nova columna.

2. Només escriu el nom de la columna (exemple: **"Testing/Review"**).

3. Si vols, pots reorganitzar les columnes fent **drag and drop** (arrossegant-les).

   ---

### **Pas 2.2: Crear les tasques (Issues)**

A **GitHub Projects**, cada incidència/tasca o unitat de treball es representa com un **"issue"** (*incidència*) o **"task"** (*tasca*). Cada _issue_ contindrà la descripció de la tasca, el temps d'execució, els membres assignats i l'estat actual.
Les Incidències són una eina de creació i seguiment d'incidències relacionades amb un projecte.

En aquest espai, també es permet la comunicació i la col·laboració entre els membres del projecte per a aportar informació sobre la incidència.

#### Per crear un **issue**:

1. A la barra lateral del projecte, fes clic a **"Issues"**.

2. Fes clic a **"New issue"**.

3. Posa un títol clar a la tasca (ex: **"Disseny de la xarxa WiFi"**).

4. Afegeix una **descripció detallada** de la tasca, com els passos a seguir o punts que inclou i el resultat de la tasca.

5. Assigna un **membre del grup** a la tasca seleccionant-los a **Assignees**.

6. Assigna una **etiqueta** si vols categoritzar les tasques (ex: **"Desenvolupament", "Revisió"**).

7. Fes clic a **Submit new issue**.

Així crearàs una tasca dins el repositori per a cada acció a realitzar.

---

### **Pas 2.3: Afegir incidències/tasques al tauler de Projectes**

1. Una vegada tingues el tauler creat, pots **afegir tasques** a les columnes.

2. Hi ha dos possibilitats:
   - Editant el _issue_, a la part dreta et permetrà seleccionar directament el **Project Board** i la **columna** (per exemple: **"Backlog"** o **"To Do"**).
   - A l'esquerra de cada _issue_ (des de la secció **Issues**), trobaràs una opció per **afegir-les al tauler de projectes**.

4. Quan crees un **Issue**, pots seleccionar directament el **Project Board** i la **columna** (per exemple: **"Backlog"** o **"To Do"**).

   ---

## **3. Assignar tasques als membres**

### **Pas 3.1: Assignar membres a les tasques**

Quan crees o editis un **Issue**, pots assignar-lo a un membre del grup:

1. Dubs de l'issue, fes clic a **Assignees**.

2. Selecciona el membre de l'equip al qual vols assignar la tasca.

### **Pas 3.2: Seguiment de l'estat de la tasca**

A mesura que els membres treballen en les tasques, poden moure els issues entre les diferents columnes per mostrar el **progrés**. 

Per exemple:  
* Quan una tasca passa de la columna **To Do** a **In Progress**, el membre que l'assignat farà clic a **"Move to In Progress"**.
* Quan es revisa o finalitza una tasca, la mou a **Review** o **Done**.

  ---

## **4. Utilitzar etiquetes per gestionar el flux de treball**

### **Pas 4.1: Crear etiquetes (Labels)**

Les etiquetes permeten categoritzar les incidències per a facilitar-ne la gestió.

1. A la secció de **Issues**, fes clic a **Labels** i selecciona **New label**.

2. Dona-li un nom a l'etiqueta (per exemple, **"Urgent"**, **"Revisió"**, etc.) i selecciona un color per a la visualització.

### **Pas 4.2: Afegir etiquetes a les incidències/tasques**

Quan crees o edites un **issue**, pots afegir les etiquetes adequades a cada tasca per facilitar el seguiment de la prioritat i tipus de tasca.

---
## **5. Utilitzar fites per gestionar el flux de treball**

### **Pas 5.1: Crear fites (Milestones)**

Les fites permeten organitzar les incidències per complir un objectiu específic. Dón un mecanisme per organitzar **Incidències** dins d'un repositori. 

S'utilitzen per **definir objectius específics en el desenvolupament del projecte**.

Cada fita conté la següent informació:
- Títol
- Descripció
- Data de venciment (Opcional)
- Percentatge de progrés, calculat respecte de les incidències obertes i tancades.


1. A la secció de **Issues**, fes clic a **Milestones** i selecciona **New Milestones**.

2. Dona-li un nom a la fita (per exemple, **"Instal·lació física"**, **"Configuracio xarxa"**, etc.) i selecciona un color per a la visualització.

### **Pas 5.2: Afegir fites a les incidències/tasques**

Quan crees o edites un **issue**, pots afegir les fites/objectius adequats a cada tasca per facilitar el seguiment de la prioritat i tipus de tasca.

---

## **6. Fer seguiment del projecte**

### **Pas 6.1: Controlar el progrés**

GitHub ofereix visualitzacions per veure ràpidament l'estat del projecte. Pots veure els **Issues** oberts, en progrés, i finalitzats directament des de l'opció **Projects** del repositori.

### **Pas 6.2: Informes i estadístiques**

Per tenir una visió més detallada del progrés, pots utilitzar **milestones** per agrupar tasques relacionades amb un **objectiu** comú o per establir terminis.

---

## **7. Comunicació i Feedback**

* **Comentaris a Issues**: Els membres poden deixar comentaris dins de cada **issue** per discutir tasques, plantejar dubtes o proporcionar feedback.

* **Pull requests**: Quan un membre completa el seu treball, fa un **pull request** per fusionar els canvis, i els altres membres poden revisar-los i aprovar-los.

  ---

## **8. Recursos addicionals**

* **[GitHub Docs](https://docs.github.com/en)**: Documentació oficial de GitHub Projects  
* **[GitHub Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects)**: GitHub està millorant la funcionalitat de "Projects" amb noves eines, com les **"Automated workflows"** per a tasques repetitives.

