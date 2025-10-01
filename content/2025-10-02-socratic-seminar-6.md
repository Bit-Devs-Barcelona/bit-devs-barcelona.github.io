+++
title = "Seminari Socràtic #6"
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

- [Compact Blocks Prefill](https://delvingbitcoin.org/t/stats-on-compact-block-reconstructions/1052/34) - David Gumberg proposa millorar la velocitat de reconstrucció de "compact blocks" pre-omplint els blocs amb algunes transaccions que pensem que els nostres peers no coneixen, evitant així algunes rondes de comunicació a l'hora de reconstruir els blocs i millorant la velocitat de construcció dels blocs.
- [Sharing block templates](https://delvingbitcoin.org/t/sharing-block-templates/1906) - AJTowns proposa compartir templates de blocs entre nodes per tal d'advertir als nostres peers sobre què pensem que serà minat en el pròxim block. La proposta ha rebut el número de [BIP 153](https://github.com/bitcoin/bips/pull/1937) i s'ha obert un [PR#33191](https://github.com/bitcoin/bitcoin/pull/33191) a Bitcoin Core per implementar-ho.
- [OP_TWEAKADD](https://github.com/bitcoin/bips/blob/4500b0ad25e3e61c58b26d563f1dcc232d21d7a8/bip-XXXX.md) - Jeremy Rubin proposes a new opcode that mirrors the Taproot tweak used by BIP340 signers. It takes an x-only public key and a 32-byte integer `h` on the stack and pushes the x-only public key corresponding to `P + h*G`, where `P` is the lifted point for the input x-coordinate and `G` is the secp256k1 generator.
- [Gran reorg a Monero](https://qubic.org/pr/qubic-overtakes-monero-s-hash-rate-in-live-51-takeover-demo) - A mitjans d'Agost, la pool de Qubic de Monero, [va aconseguir temporalment més del 50%](https://coinmetrics.substack.com/p/state-of-the-network-issue-326) del seu hashrate i va provocar una reorganització de sis blocs. Aquest incident deixa en evidenciar els riscos dels mecanismes Proof-of-Work (PoW) en xarxes més petites.

#### Estadistiques de la Xarxa
- [mempool.space](https://mempool.space/)
- [clarkmoody.com](https://bitcoin.clarkmoody.com/dashboard/)

#### Esdeveniments

#### Notícies

#### Llançaments

#### ...
