Bonjour à tous et à toutes.
J'ai créer une library pour gérer vos Db. 
Pour l'utiliser dans le builg.gradle de votre app ajouter ce code :

<code>
allprojects {
	repositories {
		maven { url 'https://jitpack.io' }
	}
}
</code>


Puis celui-ci :
<code>
dependencies {
    implementation 'com.github.LeGlitcheurDu78:DbManager:1.0'
}
</code>
