<h1 align="center">Exercice MERISE Gestion de Bibliothèque : Modèle Logique de Donnée</h1>

<code>
livre(<ins>liv_id</ins>, liv_titre, liv_date_publication, liv_nombre_page, liv_statut_emprunt, #aut_id)<br>
auteur(<ins>aut_id</ins>, aut_nom, aut_prenom)<br>
lecteur(<ins>lec_id</ins>, lec_nom, lec_prenom, lec_email, lec_telephone)<br>
manga(<ins>#liv_id</ins>, man_nom_original)<br>
scolaire(<ins>#liv_id</ins>, sco_niveau, #disc_id)<br>
enfant(<ins>#liv_id</ins>, enf_age_min, enf_age_max)<br>
discipline(<ins>disc_id</ins>, disc_nom)<br>
genre(<ins>gen_id</ins>, gen_nom)<br>

</code>

<code>
emprunter(<ins>emp_id</ins>, emp_date_emprunt, emp_date_retour, #lec_id, #liv_id)<br>
categoriser(<ins>cat_id</ins>, #gen_id, #liv_id)<br>
</code>
