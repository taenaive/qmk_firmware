# Lily58L
<img src="https://keycapsss.com/media/image/21/2b/68/lily58l-split-keyboard-rgb-led-1.jpg" width="400">

A modified Lily58 pcb, with underglow, per key rgb light and rotary encoder support.
- SK6812 Mini-E per key led's (58x) for easy soldering
- 6x SK6812 Mini led's per side for underglow
- Support for 1 rotary encoder on each side

Left encoder: volume up/down, next/previous track on RAISE layer  
Right encoder: cursor down/up, right/left on LOWER layer

- qmk compile -kb lily58/rev1 -km taenaive

- qmk flash -c -kb lily58/rev1 -km taenaive -e CONVERT_TO=elite_pi

* SS_TAP() presses and releases a key.
* SS_DOWN() presses (but does not release) a key.
* SS_UP() releases a key.

* SS_LCTL(string)
* SS_LSFT(string)
* SS_LALT(string) or SS_LOPT(string)
* SS_LGUI(string)
- SEND_STRING(SS_LCTL("a"));
- SEND_STRING("VE"SS_TAP(X_HOME)"LO");
- SEND_STRING("VE" SS_DELAY(1000) SS_TAP(X_HOME) "LO");

## italian vs french
- il manque quelque chose => manca qualcosa
- détendez vous
- où sont les toilettes? => Dov'è la toilette
- j'aimerais prendre un café => Vorrei prendere un caffè
- Peut-être => forse
- je viens des États-Unis => Vengo dagli Stati Uniti => vengo dalla Corea (je suis de la Corée) 
- je vis aux états-unis => vivo negli Stati Uniti =>io vivo in corea (je vis en corée) abito a roma.
- posso avere un bicchiere d'acqua , posso avere un pezzo di pizza?
- voglio mangiare una pizza
- vorrei una carbonara
- come stai - sto bene, grazie
- ciao, come ti chiami ? - mi chiamo stefano 
- Je suis Coréen => sono coreano
- da portare via
- mi piacciono
- posso dare la pasta a Marco? certo, dagilela
- vattene!
- non me ne frega niente => je ne m'inquiète pas
- benissimo => trés bien => muy bien
- bene grazie => bien merci
- bellissima => Maginifique
- non capisco quello che stai dicendo => Je ne comprends pas ce que vous dites
- sono andato => Je suis allé.
- tu pure => toi aussi  (Dilegua, o notte! == Va-t'en, ô nuit ! == ¡Vete, oh noche!)
- più o meno => plus ou moins
- non ho capito => Je ne comprenais pas => Ich habe es nicht verstanden
- l'addition => il conto => la cuenta => Die Rechnung, bitte
- j'ai une réservation au nom de => Ho una prenotazione a nome di => Tengo una reserva a nombre de => Ich habe eine Reservierung im Namen von
- à quelle heure le petit déjeuner => a che ora è la colazione => a que hora es el desayuno => Wann gibt es Frühstück
- quelle est mot de passe du wifi => qual è la password wifi => cual es la contraseña wifi
- puis-je laisser mes bagages à la reception? jusqu'à 16 heur => posso lasciare i bagagli alla reception? fino alle 16:00
- pourriez-vous appeler un taxi pour moi? => potresti chiamare un taxi per me? => ¿Podrías llamar un taxi para mí?
- où puis-je acheter des tickets => Dove posso acquistare i biglietti => Dónde puedo comprar las entradas
- (comment allez à) la tour eifel => come arrivare alla torre eiffel(comme andare a) => como llegar a la torre eiffel
- puis-je y aller à pied => posso camminare lì? => ¿Puedo caminar allí?
- on m'a volé mon sac => La mia borsa è stata rubata
- j'ai perdu mon passeport => Ho perso il mio passaporto => Perdí mi pasaporte
- pourriez vous me prêter votre telephone => potresti prestarmi il tuo telefono => podrías prestarme tu teléfono
- je cherche une pharmacie => Cerco una farmacia
- mi scuzi
- quanto costa questo?
- dove la stazione ?
- prendo un cappucino
- buon pomeriggio, salve
- a dopop , a presto, a domani, buona giornata, buona serata
- Va bene, grazie
- di niente, permesso ,piacere, mi scuzi, scusami
- mi servirebbe un pantalone. potrebbe aiutarmi a trovarlo? => J'ai besoin d'un pantalon. pourriez-vous m'aider à le trouver?
- proverei questa blu, grazie
- cosa desidera da bere? => Que voulez-vous boire?
- potrebbe portarci(mi) il menu(del vino della casa) per favore. => pourriez-vous nous (m')apporter le menu(du vin de la maison) s'il vous plaît
- permesso, buongiorno, piacere di conoscerla => Bonjour heureux de vous rencontrer
- prenda la chiave, per cortesia, prego entri pure, piacere
- mai bevuto così buono => jamais aussi bien bu
- lei comme si chiama? (tu comme ti chiami?)
- dove posso fare colazione (il biglietto), où puis-je prendre le petit déjeuner (obtenir le billet)
- scuzi, vorrei pagare il conto del tavolo 3

