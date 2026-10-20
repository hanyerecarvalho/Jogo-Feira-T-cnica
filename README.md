# Jogo da Feira Técnica 🎮

Projeto colaborativo de um jogo de zumbis desenvolvido em **Unity e C#** para a Feira Técnica do Colégio UNIVAP.

Este repositório é um fork de [dest-cmd/Jogo-Feira-T-cnica](https://github.com/dest-cmd/Jogo-Feira-T-cnica). Os créditos do projeto original e dos demais colaboradores devem ser preservados.

## O que há no projeto

- Movimentação do jogador e sistema de disparos.
- Munição com recarga automática.
- Menu de pausa.
- Cenas de título, tutorial, seleção de fases, vitória, game over e créditos.

## Requisitos

- Git.
- Unity Hub.
- **Unity 2017.4.40f1**, versão registrada em [ProjectSettings/ProjectVersion.txt](ProjectSettings/ProjectVersion.txt).

## Abrir e jogar no editor

```bash
git clone https://github.com/hanyerecarvalho/Jogo-Feira-T-cnica.git
cd Jogo-Feira-T-cnica
```

1. No Unity Hub, adicione a pasta clonada como projeto existente.
2. Abra com a versão do Unity indicada acima e aguarde a importação dos arquivos.
3. Abra a cena `Assets/Scenes/Tela de Titulo.unity`.
4. Clique em **Play** no editor.

Use a versão registrada antes de tentar migrar o projeto para outro editor.

## Controles

| Ação | Entrada |
| --- | --- |
| Movimentar | Eixos `Horizontal` e `Vertical`, conforme configuração de entrada do Unity |
| Atirar | Botão esquerdo do mouse |
| Pausar | `Esc` |
| Recarregar | Automaticamente quando a munição acaba |

## Estrutura

```text
Assets/Scenes/    Cenas do jogo
Assets/Scripts/   Código em C#
ProjectSettings/  Configurações e versão do Unity
```

## Contribuir

Crie uma branch para suas alterações, descreva o que mudou e abra um pull request. O acesso de escrita depende das permissões do repositório; clonar não exige convite de colaborador.

```bash
git switch -c minha-alteracao
git add caminho/do/arquivo
git commit -m "Descreve a alteração"
git push -u origin minha-alteracao
```

Teste as cenas afetadas no Unity antes de enviar alterações e preserve os arquivos `.meta` junto dos assets correspondentes.
