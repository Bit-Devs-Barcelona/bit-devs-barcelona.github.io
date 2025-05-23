+++
title = "Seminari Socràtic #4"
template = "post.html"
draft = false
+++

### Agenda
18:00h Presentacions\
19:00h Seminari Socràtic on es revisaran múltiples temes relacionats amb Bitcoin\
20:00h Tancament

### Ubicació
Escola d'Enginyeria de la Universitat Autònoma de Barcelona.\
La localització exacta s'enviarà per missatge directe als assistents.

### Anuncis
Estem molt contents de poder presentar el nostre quart [Seminari Socràtic](/about)!\
Agraiments a [B4OS](https://www.libreriadesatoshi.com/b4os) per ajudar amb algunes despeses del projecte i a la UAB per l'espai.

### Recordatoris
- No es faran fotografies ni vídeos de les cares dels participants sense el seu consentiment.
- Proposa temes pel Seminari Socràtic! [Pots obrir una issue al repo de GitHub](https://github.com/Bit-Devs-Barcelona/bit-devs-barcelona.github.io/issues) proposant un tema per parlar. [On trobar temes?](/about/find-topics/)

### Temes

- [Erlay](https://arxiv.org/pdf/1905.10518) és un protocol eficient en amplada de banda per a la retransmissió de transaccions a la xarxa P2P de Bitcoin, construït sobre [BIP330](https://github.com/bitcoin/bips/blob/master/bip-0330.mediawiki), que permet una reconciliació eficient dels anuncis de transaccions. Consulta el [seguiment del projecte](https://github.com/bitcoin/bitcoin/issues/30249). (Format presentació per [Sergi Delgado](https://srgi.me/))

- **Please god not OP_RETURN filters:** Per què no volem una discrepància entre el que hi ha la mempool i el que realment entra en el següent bloc? Com afecta això als incentius miners? Per què fa més difícil l'estimació de taxes? Com afecta a la Lightning Network? És la política de mempool personalitzable per l'usuari un atzucac? [Xerrada de la Gloria Zhao sobre les polítiques de la mempool](https://vimeo.com/704956163). Més context a la [Issue](https://github.com/Bit-Devs-Barcelona/bit-devs-barcelona.github.io/issues/13).

- **Costa molt calcular un hash?** Tots nosaltres, en el primer moment que vam entendre com es generaven les claus de Bitcoin i com es gastaven els bitcoins, hem pensat que seria una bona idea generar claus aleatòries i mirar si l'adreça corresponent bloqueja algun UTXO. Per fer-ho, cal generar la clau privada, calcular la pública i fer el hash (assumint que l'UTXO està en una P2PKH o P2WPKH). Aquesta última acció (fer el hash) s'evita si l'UTXO està en una P2PK o coneixes la clau pública que bloqueja l'UTXO. Però, aquest últim pas de fer el hash, realment retarda molt la feina quan estàs provant amb força bruta moltes claus? Doncs sembla que sí, a jutjar pels challenges que s'han resolt i els que no d'aquest [multi-challenge](https://privatekeys.pw/puzzles/bitcoin-puzzle-tx).


- [Cluster mempool](https://bitcoinops.org/en/topics/cluster-mempool/) és una proposta per millorar els algorismes de mining i eviction de la mempool. Links d'interès: [Tracking issue](https://github.com/bitcoin/bitcoin/issues/30289) - [Cluster mempool definitions & theory](https://delvingbitcoin.org/t/cluster-mempool-definitions-theory/202)


#### Estadistiques de la Xarxa
- [mempool.space](https://mempool.space/)
- [clarkmoody.com](https://bitcoin.clarkmoody.com/dashboard/)

#### Esdeveniments

#### Notícies

#### Llançaments

#### ...
