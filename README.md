Bonjour à tous et à toutes.
J'ai créer une library pour gérer vos Db. 
Pour l'utiliser dans le builg.gradle de votre app ajouter ce code :

<code>
<pre>
allprojects {
	repositories {
		maven { url 'https://jitpack.io' }
	}
}
</pre>
</code>


Puis celui-ci :

<code>
<pre>
dependencies {
    implementation 'com.github.LeGlitcheurDu78:DbManager:1.0'
}
</pre>
</code>
