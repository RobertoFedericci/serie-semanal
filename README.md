# Página estática protegida

Página única, com conteúdo cifrado (AES-256 / PBKDF2, via StatiCrypt).
Não há outros arquivos: layout, código e dados vivem cifrados dentro de `index.html`.

Requer HTTPS — a decifragem usa WebCrypto, disponível apenas em contexto seguro.
Acesso mediante senha, distribuída fora deste repositório.
