+++
title = "Seminari Socràtic #17"
template = "post.html"
draft = false
+++

### Agenda
18:00h Presentacions\
18:15h Seminari Socràtic on es revisaran múltiples temes relacionats amb Bitcoin\
20:00h Tancament

### Ubicació
Escola d'Enginyeria de la Universitat Autònoma de Barcelona. [Google Maps]\
Aula Shannon - Agafeu l'ascensor a l'entrada fins a la 2a planta. Sortint de l'ascensor a l'esquerra, l'aula Shannon queda a l'esquerra del passadís.

### Anuncis
Estem molt contents de poder presentar el nostre setzè [Seminari Socràtic](/about)!\
Agraiments a [B4OS](https://www.libreriadesatoshi.com/b4os) i [Bitronics](https://bitronics.store/) per ajudar amb algunes despeses del projecte i a la UAB per l'espai.

### Recordatoris
- No es faran fotografies ni vídeos de les cares dels participants sense el seu consentiment.
- Proposa temes pel Seminari Socràtic! [Pots obrir una issue al repo de GitHub](https://github.com/Bit-Devs-Barcelona/bit-devs-barcelona.github.io/issues) proposant un tema per parlar. [On trobar temes?](/about/find-topics/)

### Temes

##### Consens i protocol
- [Hashrate wars](https://github.com/Bit-Devs-Barcelona/bit-devs-barcelona.github.io/issues/66) - Debat sobre l'impacte del desajust entre l'adopció de nodes i l'adopció de hashrate en l'èxit dels soft forks, arran del BIP110: què passa quan un soft fork té poc hashrate al darrere i els nodes l'acaben abandonant pels temps de bloc llargs de la cadena del fork.
- [BIP448: Taproot-native (Re)bindable Transactions](https://github.com/bitcoin/bips/blob/master/bip-0448.md) - This is a draft soft fork by Greg Sanders, Antoine Poinsot and Steven Roose. It bundles OP_TEMPLATEHASH (BIP446), OP_CHECKSIGFROMSTACK (BIP348) and OP_INTERNALKEY (BIP349) into tapscript to enable rebindable signatures: a signature committing to a template hash instead of a specific input, so it can spend any output with a matching script. Use cases: LN-Symmetry (eltoo), multiparty channels, simpler statechains, Ark variants, delegation and simple vaults: [The f2pool is open to signal](https://x.com/satofishi/status/2107603873661596096).
- [Shielded bitcoin](https://x.com/allocinitxyz/status/2103124026214568209) - Transaccions confidencials a Bitcoin.

##### Bitcoin Core
- [Bitcoin Core v32.0](https://github.com/bitcoin/bitcoin/blob/32.x/doc/release-notes.md) - Canvis principals: obtenció paral·lela de prevouts de la chainstate (`-prevoutfetchthreads`), que segons alguns informes fa l'IBD fins a 3 vegades més ràpid; un segon estimator de comissions que també mira la mempool; nous RPCs (`exportwatchonlywallet`, `exportasmap`, `getopenrpcinfo`); PSBTv2 per defecte; taproot eliminat de `getdeploymentinfo`.
- [New prunned assumevalid proposal in bitcoin core](https://github.com/bitcoin/bitcoin/issues/36476) - Mode `assumevalid` podat opt-in que descarrega blocs sense testimonis, els manté en memòria i els deserialitza i connecta sense escriure blocs ni undo data a disc. En proves inicials, l'IBD podat en una Raspberry Pi 4 de 2 GB passa de ~22 dies a menys d'una setmana (3 dies en un prototip anterior), cosa que podria tornar a fer pràctics els dispositius de gamma baixa.

##### Wallets i seguretat
- [Bunker mode](https://x.com/drakefjustin/status/2107837081313505768) - Justin Drake fa una crida a entrar en «mode búnquer». Adverteix que els avenços en intel·ligència artificial podrien comprometre la seguretat de la criptografia de les carteres (ECDSA) abans de l'arribada de la computació quàntica.
- [Savepoint Signer](https://github.com/alvroble/savepoint-signer) - L'Álvaro, un dels desenvolupadors de SeedSigner, ha modificat el Pokémon Crystal per poder signar una PSBT dins del mateix joc en una Game Boy.
- [Més de 86 M$ robats a usuaris de Ledger al sud-est asiàtic](https://x.com/Ledger_Support/status/2108551100613714002) - El robatori sembla lligat a un revenedor anomenat CryptoBillis i no a una vulnerabilitat del programari. Apunta a un atac de cadena de subministrament ([fil de MagicalTux](https://x.com/MagicalTux/status/2108576506704548179)) i ja s'està veient també a Europa ([actualització](https://x.com/0xJohannes_/status/2109634517296148568)).
- [Second's Ark explotat per 0,75 BTC](https://x.com/secondhq/status/2108065406665805992) - Un atacant va explotar un bug al servidor d'Ark de Second el 5 d'octubre i va robar 0,75 BTC de la liquiditat de la mateixa empresa ([anunci](https://x.com/BitcoinNewsCom/status/2108173726789321183)).

##### Eines i desenvolupament
- [bitfiles](https://github.com/bitfiles-io/bpub) - Permet incrustar dades arbitràries a Bitcoin (i a Blake2b) codificant-les en suposades pubkeys comprimides de secp256k1. Sembla que algú ja ha començat a encodar un munt d'imatges a la cadena de Blake2b ([bitfiles.io/btcb2](https://bitfiles.io/btcb2)).
- [Reboot de secp256k1-php](https://github.com/1ma/secp256k1-php) - Antigament es podia fer servir libsecp256k1 des de PHP amb una extensió nativa escrita en C que portava 7 anys sense rebre manteniment i que no compilava amb cap versió recent de PHP. Ara s'ha rellançat el projecte.

#### Estadistiques de la Xarxa
- [mempool.space](https://mempool.space/)
- [clarkmoody.com](https://bitcoin.clarkmoody.com/dashboard/)

#### Esdeveniments


#### Notícies

#### Llançaments

#### ...


[Google Maps]: https://maps.app.goo.gl/a6EQgpF9yjr68nhV9
