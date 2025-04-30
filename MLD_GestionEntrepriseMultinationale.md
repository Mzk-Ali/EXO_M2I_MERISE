<h1 align="center">Exercice MERISE Gestion Entreprise Multinationale : Modèle Logique de Donnée</h1>

<code>
employe(<ins>emp_id</ins>, emp_nom, emp_prenom, emp_date_naissance, emp_date_embauche, emp_salaire)<br>
projet(<ins>pro_id</ins>, pro_code, pro_titre, pro_date_debut, pro_date_fin)<br>
tache(<ins>tac_id</ins>, tac_titre, tac_description, tac_date_debut, tac_debut_fin, tac_statut)<br>
departement(<ins>dep_id</ins>, dep_nom, #dep_parent_id, #emp_responsable_id)<br>
manager(<ins>#emp_id</ins>, man_budget, man_bureau)<br>
technicien(<ins>#emp_id</ins>, tech_specialite, tech_niveau_competence)<br>
</code>

<code>
employe_departement(<ins>ep_id</ins>, #emp_id, #dep_id)
projet_departement(<ins>pd_id</ins>, #dep_id, #pro_id)
employe_projet(<ins>ep_id</ins>, #emp_id, #pro_id)
projet_tache(<ins>pt_id</ins>, #tac_id, #pro_id)
employe_tache(<ins>et_id</ins>, #emp_id, #tac_id)
</code>
