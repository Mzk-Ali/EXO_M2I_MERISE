<h1 align="center">Exercice MERISE GestionMagasin : Modèle Logique de Donnée</h1>

<code>
client(<ins>cli_id</ins>, cli_email, cli_nom, cli_prenom, cli_rue, #vil_id)<br>
produit(<ins>prod_id</ins>, prod_nom, prod_prix_unitaire, prod_libelle)<br>
categorie(<ins>cat_id</ins>, cat_nom, #categorie_parent_id)<br>
commande(<ins>com_id</ins>, com_ref, com_date, com_rue, #cli_id, #vil_id)<br>
ville(<ins>vil_id</ins>, vil_cp, vil_ville)<br>
</code>

<code>
contenir(<ins>cont_id</ins>, con_quantite, #prod_id, #com_id)
categoriser(<ins>categoriser_id</ins>, #cat_id, #prod_id)
</code>
