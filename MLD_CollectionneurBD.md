<h1 align="center">Exercice MERISE Collectionneur de BD : Modèle Logique de Donnée</h1>

<code>
BD(<ins>bd_id</ins>, bd_numero, bd_titre, bd_date_parution, bd_parution_actuel, #per_editeur_id, #lan_id, #sty_id, #serie_id)<br>
personne(<ins>per_id</ins>, per_nom, per_prenom)<br>
parution(<ins>par_id</ins>, par_libelle)<br>
langue(<ins>lan_id</ins>, lan_langue)<br>
style(<ins>sty_id</ins>, sty_nom)<br>
metier(<ins>met_id</ins>, met_nom)<br>
serie(<ins>serie_id</ins>, serie_nom)<br>
</code>

<code>
archivage(<ins>arch_id</ins>, arch_date, #par_id, #bd_id)<br>
exercer(<ins>exe_id</ins>, #met_id, #per_id)<br>
ecrit(<ins>ecr_id</ins>, #per_id, #bd_id)<br>
dessiner(<ins>des_id</ins>, #per_id, #bd_id)<br>
colorier(<ins>col_id</ins>, #per_id, #bd_id)<br>
</code>
