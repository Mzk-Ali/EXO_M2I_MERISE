<h1 align="center">Exercice MERISE Historien : Modèle Logique de Donnée</h1>

<code>
soldat(<ins>sol_id</ins>, sol_nom, sol_prenom, sol_date_naissance, sol_date_deces, #vil_id, #bat_id)<br>
bataille(<ins>bat_id</ins>, bat_lieu, bat_debut, bat_fin)<br>
grade(<ins>gra_id</ins>, gra_nom)<br>
ville(<ins>vil_id</ins>, vil_nom, vil_cp)<br>
unite_rattachement(<ins>uni_id</ins>, uni_nom)><br>
blessure(<ins>ble_id</ins>, ble_type)
</code>

<code>
obtenir(<ins>obt_id</ins>, obt_date, #sol_id, #gra_id)<br>
blesser(<ins>ble_id</ins>, ble_date, #sol_id, #bat_id, #ble_id)<br>
rattacher(<ins>rat_id</ins>, #sol_id, #uni_id)<br>
</code>
