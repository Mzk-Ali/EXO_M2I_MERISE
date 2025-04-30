<h1 align="center">Exercice MERISE GestionMagasin : Modèle Logique de Donnée</h1>

<code>
personne(<ins>per_id</ins>, per_email, per_nom, per_prenom, per_date_naissance, per_rue, #vil_id)<br>
ville(<ins>vil_id</ins>, vil_cp, vil_ville)<br>
cours(<ins>cou_id</ins>, cou_titre, cou_date_debut, cou_date_fin, #per_instructeur_id)<br>
instructeur(<ins>#per_id</ins>)<br>
membre(<ins>#per_id</ins>)<br>
type(<ins>type_id</ins>, type_libelle)<br>
</code>

<code>
assister(<ins>ass_id</ins>, #per_id, #cou_id)
</code>
