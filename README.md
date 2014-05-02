Gladys
======
L'objectif est de construire � l'aide d'un Raspberry Pi un syst�me similaire au JARVIS du film Iron Man, capable de g�rer la maison, diffuser des news, de la musique, lancer un r�veil, etc...

Vous allez me dire : plein de projets existent d�j�! et pourtant �a ressemble bien souvent � du bricolage!

En fait, je pars sur une toute autre approche. Bien souvent, les projets JARVIS sont des sortes de siri, l'utilisateur pose une question ("Quel temps fait-il ?"), le syst�me analyse la voix, et fournit une r�ponse. Le probl�me, c'est que la reconnaissance vocale, en 2014, c'est pas encore �a... et encore moins sous linux.

Alors j'ai pris le probl�me � l'envers : Et si au lieu que �a soit l'homme qui sollicite vocalement l'assistant, �a soit l'assistant qui sollicite l'homme au bon moment ?
C'est � dire qu'au lieu que ce soit l'utilisateur qui pose une question, �a soit l'assistant qui prenne la parole, ou fasse une action, pour aider l'utilisateur.

Imaginons un sc�nario :
- Il est 8H, Gladys me r�veille car elle sait qu'� 9H je dois aller travailler, et que je mets, selon mes pr�f�rences, 1 heure pour me pr�parer et aller au boulot. Elle a vu gr�ce � une API de m�t�o qu'il pleut dehors, et en profite pour me le signaler au r�veil. D�s que je sors de mon lit, elle d�tecte un mouvement dans la pi�ce et coupe le r�veil, allume la lumi�re, et lance une playlist/la radio.
- Il est 8H45, je sors de chez moi pour aller travailler, Gladys d�tecte que je ne suis plus l�, elle coupe lumi�re, musique, etc...
- Cependant, apr�s le boulot, je sors chez des amis, et reste dormir chez eux. Gladys sait que je ne suis pas rentr� (pas de mouvement), et d�sactive donc le r�veil du lendemain, car pas besoin de sonner si je ne dors pas chez moi, et que mon appartement est vide !
- Le lendemain, 8H, Gladys m'envoie une notification sur mon portable pour me rappeler qu'a 9H je dois �tre au bureau.
- 19H, je rentres du bureau, Gladys allume la lumi�re, me souhaite la bienvenue, et me notifie les messages que j'ai re�u en mon absence
Ainsi, au lieu d'un syst�me passif qui attend des commandes de l'utilisateur, nous avons ici un v�ritable assistant qui aide l'utilisateur au quotidien en prenant des iniatives. Et ce n'est pas futuriste ! Toutes les technos cit�es ci-dessus existent...

Gladys est maintenant disponible au t�l�chargement, vous pouvez la t�l�charger depuis cette page : http://intelligenceonline.synergize.co/