# DM-LAB-1-HelloToast
But du lab
Créer une petite application qui affiche un message Toast et un compteur.
Deux boutons seront présents :
Afficher un message “Toast” lorsque l’utilisateur clique dessus ;
Incrémenter un compteur affiché à l’écran.

---

Étape 1 – Création du projet
Ouvrir Android Studio.
Choisir New Project → Empty Activity.
Nom du projet : HelloToast.
Langage : Java.
API minimum : 24 (Android 7.0).

![Import OVA](https://github.com/user-attachments/assets/e0548f9f-2abf-4cc8-a93d-1362d4edcaf7)

![Import OVA](https://github.com/user-attachments/assets/e8ed3514-6bc7-4e92-a91f-61633e214d86)

--- 

Étape 2 – Conception de l’interface
Les interfaces Android sont décrites en XML.
Chaque élément visuel correspond à une balise (<TextView>, <Button>, etc.).
👉 Ouvrir le fichier :
res/layout/activity_main.xml

![Import OVA](https://github.com/user-attachments/assets/5ffd1243-00a1-4ded-9795-e2bd9c4b3f91)

Explication
LinearLayout : organise les éléments verticalement.
TextView : zone de texte non modifiable (ici, le compteur).
Button : bouton cliquable.
android:id="@+id/...“ : identifiant pour retrouver l’élément en Java.

---

Étape 3 – Logique Java (MainActivity.java)

![Import OVA](https://github.com/user-attachments/assets/1cd48519-73e5-40f4-bc2c-c83a4d23e65a)



