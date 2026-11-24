# Aviso de queda do GeoUrbano

A cada 15 minutos, o GitHub confere se o app (`https://app.geourbano.ia.br`) e o site (`https://www.geourbano.ia.br`)
respondem e se o certificado do app vale por mais de 14 dias. Cada teste tenta 3 vezes antes de dar falha. Se falhar,
o GitHub manda e-mail para o dono deste repositório.

Repositório público de propósito: só testa endereços públicos, não guarda nenhum segredo, e em repositório público o
GitHub Actions não cobra minutos. Uma vez por mês o próprio workflow grava um "sinal de vida", porque o GitHub desliga o
agendamento de repositório público que fica 60 dias sem atividade.
