<h1 align="center">Exercice MERISE Reservation de Salle : Modèle Logique de Donnée</h1>

<code>
personne(<ins>per_id</ins>, per_email, per_nom, per_prenom, per_telephone, #per_superieur_id, #ser_id)<br>
reservation(<ins>res_id</ins>, res_date, res_heure_debut, res_duree, res_statut_actuel, #per_reservation_id, #type_id, #sal_id)<br>
salle(<ins>sal_id</ins>, sal_nom, sal_capacite)<br>
type(<ins>type_id</ins>, type_libelle)<br>
service(<ins>ser_id</ins>, ser_nom)<br>
</code>

<code>
archiver(<ins>arch_id</ins>, arch_statut, arch_date, #per_id, #res_id)<br>
participer(<ins>par_id</ins>, #per_id, #res_id)<br>
</code>
