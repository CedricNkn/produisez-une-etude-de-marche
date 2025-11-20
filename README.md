# Produisez-une-etude-de-marche avec R ou python

<div class="oc-richContent root-0-3-1" data-videotitle="video" data-current-user-id="12483588" data-project-id="862" data-current-user-email="cedric.nkn@gmail.com" data-token-rootme="eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiJ9.eyJhdWQiOiI5ZTg4Njk1Ny0wZWM3LTQwM2EtOTBkNy05NGFhNTU0MmNlYjMiLCJqdGkiOiI4Nzc2OGM1YTFlMzc5OTI5ODQyZGFjYjcxNzAxMWVlMjg5ZjcxMGU1N2U3YTgxMmJmNmQ0NGEyMTYxOWU3YmQxNTY0ODgzODQ1YTRjMWUzMSIsImlhdCI6MTc0NDI3MDQ1NS45MTQyMjEsIm5iZiI6MTc0NDI3MDQ1NS45MTQyMjMsImV4cCI6MTc3NTgwNjQ1NS45MDc1NzMsInN1YiI6IjAxOTVkODFmLTc5ODMtNzJiZC1iNzI4LTc5NGI4YTU2OTFjMCIsInNjb3BlcyI6W119.eOMnO6XDnzFZIIu4U4acICW0PfK6nJHNJL7Dr7Q4p5KGMLBT5k5vMlNrqUzsIZVHUhhg21LFM2Cwi0mcT5ca3kOLMoZSFaJwJLBdFloVs1zGGZr0ABuCEcUrAYBPjo8318r5LnoHGQ6lxZE_5AKA-2BoTRPfMHXiRHRzfRrjKlhFvW0n4GMs2B3XY28tNtWHp_H1KJCAiRdZb8OivPTEYPpxaomZEmt27FbduEvjknUZGivn4ldhJtNThyu8Bp5IC0idBvC6SznWdzf82OvK4dbqY4mUE9D0SPDsGIjb4kcQawP3gkIplPE2dubrDixuTY8GCp4ZwhgO4SPcN_vm9SG85r0uhVklgnIJw9THJ7ZXKNPZUaZYSA6cMOoeOxCgOEBbmsDj5i5NlymaUmKzmVH2LFgTwdrTveDYcDwFhzMvEjEE_aeI3yDx5-uVBSlgg46bNu0B8locaH0m3W0Sd9A3ZJqj64ySJgtblqEILpvWK_4d1Gc6VPN8Y-iOpfHmc-XZKmNexpIeaOuSOcX7MeAI4umJ3mdidJW2WCB36WN3GW7GLN8z9-4r0G5wOOWgRSj7ilYoMCv51_pXH1ffJEjD-JUJE2jWnKFsJWte93fZK5i9wqf7c8GPWkgoRGFONWe3t-lM3mEwe6hVVpZ6Mdb1NnTfCWJW56ZKFRh-m4M" data-margin="no-margin" data-translations="{&quot;forbiddenError&quot;:&quot;Vous ne pouvez actuellement pas accéder à ce projet. Assurez vous de bien être positionné sur ce projet par votre mentor.&quot;,&quot;genericError&quot;:&quot;Une erreur est survenue. Veuillez réessayer plus tard.&quot;,&quot;invitation_sent&quot;:&quot;Invitation envoyée&quot;,&quot;invitation_already_sent&quot;:&quot;Un compte existe déjà ou une invitation est en cours. Vous avez été redirigé vers le challenge.&quot;}" data-student-id="12483588" data-student-email="cedric.nkn@gmail.com" data-student-first-name="Cedric" data-student-last-name="Nkene Mbia Bene" data-path-title=""><p>&nbsp;</p>
<p><img src="https://user.oc-static.com/upload/2023/05/24/16849360706346_OC-Bannieres-Projet_Student-Scenario_Scenario.png" alt="Scénario">&nbsp;</p>
<p>Vous travaillez chez La poule qui chante, une entreprise française d’agroalimentaire. Elle souhaite se développer à l'international.</p>
<p><img src="https://user.oc-static.com/upload/2020/11/24/16062164030098_image2.png" alt=""></p>
<p>L'international, oui, mais pour l'instant, le champ des possibles est bien large : aucun pays particulier ni aucun continent n'est pour le moment choisi. Tous les pays sont envisageables !</p>
<p>&nbsp;</p>
<p>Votre manager, Patrick, vous briefe par un e-mail :</p>
<p>&nbsp;</p>
<div class="oc-tableContainer"><table>
<tbody>
<tr>
<td><strong>De</strong>&nbsp;: Patrick<br><strong>À&nbsp;</strong>: Moi<br><strong>Objet</strong>&nbsp;: Lancement mission data international</td>
</tr>
<tr>
<td>
<p>Salut !</p>
<p>&nbsp;</p>
<p>Comme on en a déjà brièvement parlé, je te fais ce mail pour te briefer sur la mission d’analyse pour le lancement à l’international.</p>
<p>&nbsp;</p>
<p>Ton objectif sera de proposer une première analyse des groupements de pays que l’on peut cibler pour exporter nos poulets. Nous approfondirons ensuite l'étude de marché.&nbsp;</p>
<p>&nbsp;</p>
<p>Tu seras en totale autonomie sur ce projet, notamment sur le choix des données à analyser et même du langage à utiliser (R ou Python).&nbsp;</p>
<p>&nbsp;</p>
<p>Pars des données de la FAO&nbsp;<em>(Food and Agriculture Organization)</em>&nbsp;que je te mets en pièce jointe pour faire ton analyse. Si tu veux aller plus loin, notamment avec les critères de l’analyse PESTEL, tu peux récupérer et utiliser toutes les données en&nbsp;<em>open data</em>&nbsp;que tu souhaites sur&nbsp;<a class="custom-link" href="http://www.fao.org/faostat/fr/#data/">le site de la FAO</a>.</p>
<p>&nbsp;</p>
<p>Pour la partie analyse, dans un premier temps j’aimerais que tu testes la classification ascendante hiérarchique, avec un dendrogramme comme visualisation. Ensuite tu pourras utiliser la méthode des k-means, afin d’affiner l’analyse et comparer les résultats des deux méthodes de clustering. N'hésite pas à prendre le temps d’analyser les centroïdes de tes classes. Tu peux également réaliser une ACP afin de visualiser les résultats de ton analyse, comprendre les groupes, les liens entre les variables, les liens entre les individus...</p>
<p>&nbsp;</p>
<p>Voici ce que j’attends de toi :</p>
<ul>
<li>un notebook ou fichier R contenant la préparation, le nettoyage et l’analyse exploratoire des données ;</li>
<li>un notebook ou fichier R contenant le/les clusterings effectués, et les différentes visualisations associées ;</li>
<li>une présentation qui récapitule les points suivants :&nbsp;</li>
<ul>
<li>le contexte du projet de data analyse ;</li>
<li>ta&nbsp;démarche (sans entrer dans les détails mathématiques, mais en vulgarisant les sujets abordés) ;</li>
<li>tes&nbsp;résultats et recommandations.</li>
</ul>
</ul>
<p>&nbsp;</p>
<p>Bon courage !</p>
<p>Patrick</p>
</td>
</tr>
<tr>
<td>
<p>Pièce jointe :</p>
<ul>
<li><a class="custom-link" href="https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-analyst/DAN-P9-data.zip">Données New Food Balances (FAO)</a></li>
</ul>
</td>
</tr>
</tbody>
</table></div>
<p>&nbsp;Vous avez toutes les cartes en main. À vous de jouer !</p>
<p><img src="https://user.oc-static.com/upload/2023/05/24/16849361265465_OC-Bannieres-Projet_Student-Scenario_Livrables.png" alt="Livrables"></p>
<ol>
<li>Un <strong>notebook ou fichier R</strong> contenant la préparation, le nettoyage et l’analyse exploratoire des données.</li>
<li>Un <strong>notebook ou fichier R</strong> contenant le/les clusterings effectués, et les différentes visualisations associées.</li>
<li>Une <strong>présentation</strong> du travail réalisé (Powerpoint ou équivalent, maximum 20 slides).</li>
</ol>
