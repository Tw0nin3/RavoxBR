# Ravox BR

Interface personalizada para o YouTube. A versão 3.3.0 é distribuída como um userscript editável.

O endereço do projeto é [Tw0nin3/RavoxBR](https://github.com/Tw0nin3/RavoxBR). Baixe `ravox-br.user.js` nos [Releases do projeto](https://github.com/Tw0nin3/RavoxBR/releases).

## Novidades da versão 3.3.0

- Requisições com limite de tempo e cancelamento ao trocar de página ou vídeo.
- Correções no SponsorBlock, nos metadados do player e nas sugestões de pesquisa.
- Exportação, importação e restauração das configurações.
- Diagnóstico copiável sem cookies, credenciais ou URLs privadas.
- Recuperação para a interface original do YouTube após falhas graves.
- Controle separado para o bloqueio de telemetria.
- Reconhecimento correto de contagens brasileiras como “1,2 mil”, milhões e bilhões.

## Instalação e verificação

1. Baixe `ravox-br.user.js` da release oficial e abra o arquivo no Violentmonkey ou Tampermonkey.
2. Compare o SHA-256 do arquivo com o valor em `SHA256SUMS`, disponível na mesma release e no repositório. No PowerShell, use `Get-FileHash -Algorithm SHA256 ravox-br.user.js`.
3. Desative qualquer cópia antiga ou duplicada do Ravox BR e recarregue o YouTube.

## Validação

A versão passou por 16 testes automatizados de sintaxe e lógica. Eles cobrem cancelamento de requisições, troca rápida de vídeo, SponsorBlock, anúncios, playlists, navegação, backup e privacidade do diagnóstico. Como o YouTube muda com frequência, o funcionamento também deve ser conferido no navegador após a instalação.

## Créditos e licença

- Tw0nin3 é o responsável pelo Ravox BR e por suas alterações.
- O código é distribuído sob GPL-3.0-or-later. Consulte o texto em [LICENSE](LICENSE).
