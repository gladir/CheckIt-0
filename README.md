# CheckIt-0
Clone des commandes du CheckIt écrit en Pascal.

![image](https://user-images.githubusercontent.com/11842176/173472724-97e50fd0-eed4-4e71-98c6-b6ac585030a8.png)

<h2>Liste des fichiers</h2>

Voici la liste des différents fichiers proposés dans CheckIt-0 :

<table>
		<tr>
			<th>Nom</th>
			<th>Description</th>	
		</tr>
	        <tr>
			<td><b>CHECKIT.PAS</b></td>
			<td>Cette commande permet de lancer le menu de CheckIt. Cette commande est une clone de la série d'utilitaires <a href="https://www.gladir.com/SOFTWARE/CHECKIT/presentation.htm">CheckIt</a>.</td>
		</tr>
		<tr>
			<td><b>CKCMOS.PAS</b></td>
			<td>Cette commande permet de sauvegarder ou restaurer les données du CMOS du système. Cette commande est un clone de la commande <a href="https://www.gladir.com/SOFTWARE/CHECKIT/ckcmos.htm">CKCMOS</a> de la série d'utilitaires <a href="https://www.gladir.com/SOFTWARE/CHECKIT/presentation.htm">CheckIt</a>.</td>
		</tr>
</table>

<h3>Remarque</h3>
<ul>
	<li>La commande "CKCMOS.PAS" a été bonifié de la commande /AMDEK pour rechercher sur les micro-ordinateurs <a href="https://www.gladir.com/LEXIQUE/SYSTEM/amdeksystem88.htm">Admek System/88</a>.</li>
</ul>


<h2>Compilation</h2>
	
Les fichiers Pascal n'ont aucune dépendances, il suffit de télécharger le fichier désiré et de le compiler avec Free Pascal avec la syntaxe de commande  :

<pre><b>fpc</b> <i>LEFICHIER.PAS</i></pre>
	
Sinon, vous pouvez également le compiler avec le Turbo Pascal à l'aide de la syntaxe de commande suivante :	

<pre><b>tpc</b> <i>LEFICHIER.PAS</i></pre>
	
Par exemple, si vous voulez compiler CKCMOS.PAS, vous devrez tapez la commande suivante :

<pre><b>fpc</b> CKCMOS.PAS</pre>

<h2>Licence</h2>
<ul>
 <li>Le code source est publié sous la licence <a href="https://github.com/gladir/CheckIt-0/blob/main/LICENSE">MIT</a>.</li>
 <li>Le paquet original est publié sous la licence <a href="https://github.com/gladir/CheckIt-0/blob/main/LICENSE">MIT</a>.</li>
</ul>
