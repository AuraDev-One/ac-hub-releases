# AC HUB — Releases oficiais

Este repositório contém somente instaladores, assinaturas e o manifesto de atualização do AC HUB para Windows x64.

## Beta local

A versão 0.2.0-beta.3 corrige a falha geral de preparação de tráfego por caminhos vazios no executável, acrescenta detecção automática de instalações e provisionamento de ferramentas. Inclui Race Control, licença por chave e atualizações assinadas. O serviço de ativação ainda é local: o CL HUB Bot deve estar no mesmo computador, ouvindo em 127.0.0.1:3002. Não é uma versão pronta para vender ou ativar remotamente.

O Hub detecta bibliotecas Steam e instalações existentes. AssettoServer e Content Manager ausentes podem ser baixados das fontes oficiais para uma pasta própria. Jogo, CSP, DLCs e mods são instalados separadamente. Nenhum mod ou credencial do bot acompanha o instalador.

As chaves duram 7, 30, 90 dias ou Lifetime, a partir da ativação. As atualizações são verificadas pelo aplicativo; a instalação exige encerrar a sessão.
