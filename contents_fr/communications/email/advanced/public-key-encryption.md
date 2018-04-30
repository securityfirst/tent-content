[Title]: # (Chiffrement par clé publique)
[Order]: # (1)

PGP est fondé sur le concept de chiffrement par clé publique. C’est un système cryptographique qui utilise deux clés : une clé publique connue de tous et une clé privée connue seulement par le destinataire du message. Si Pierre veut envoyer un message sécurisé à Marie, il utilise la clé publique de Marie pour chiffrer le message. Marie utilise ensuite sa clé privée pour le déchiffrer.

* Le chiffrement par clé publique vous permet donc de chiffrer et d’envoyer des messages en toute sécurité à des personnes dont vous connaissez la clé publique.
* Si d’autres connaissent votre clé publique, ils peuvent vous envoyer des messages que vous seul pouvez décoder.
* Et si des personnes connaissent votre clé publique, vous pouvez leur envoyer des messages signés afin que ses personnes sachent qu’ils ne peuvent venir que de vous.
* Si vous connaissez la clé publique de quelqu’un, vous pouvez décoder un message provenant de cette personne et savoir qu’il venait bien de cette personne.

Vous devriez conserver votre clé privée en lieu sûr, protégée par mot de passe long ou une phrase de passe. (Si quelqu’un obtenait une copie de votre clé privée, il pourrait prétendre être vous et signer des messages en votre nom.) Vous pouvez donner votre clé privée à toute personne avec qui vous souhaitez communiquer, ou qui souhaite savoir si un message provient vraiment de vous.