<div align="center">

<img src="docs/assets/banner.svg" alt="Planejar viagem: roteiro, custos e clima" width="100%">

# Planejar viagem

**Do primeiro trecho ao último retorno, em um guia HTML que abre offline.**

[English](README.en.md) · [Instalação](#instalação) · [Documentação](#documentação)

</div>

Skill para agentes planejarem viagens, bate-voltas e feriados para uma ou duas pessoas. Ela compara ida, volta, hospedagem, deslocamentos, comida local e atrações; respeita o orçamento e os meios de transporte informados; e separa estimativa de reserva, emissão e pagamento.

## Como funciona

1. Reaproveita o contexto e pergunta apenas pelos dados que faltam.
2. Confere horários, custos e conexões em fontes para as datas informadas.
3. Entrega um guia visual com roteiro diário, clima, roupas, cuidados e alternativas.
4. Quando já houve compra, concilia comprovantes e recalcula o saldo sem dupla contagem.

A skill **não compra, não reserva e não contata ninguém por conta própria**. Links e mapas externos precisam de internet; o guia e suas imagens incorporadas podem ser lidos offline.

## Instalação

Clone este repositório a partir de uma conta com acesso. Copie a pasta inteira `skills/planejar-viagem` para o diretório de skills reconhecido pelo seu agente (no Codex, `~/.agents/skills/` é uma opção). Preserve `assets/roteiro.html` ao lado de `SKILL.md`.

Teste com uma viagem fictícia ou com dados não identificáveis. Exemplo: “Planeje um bate-volta para duas pessoas saindo de uma estação central, só de trem e a pé, com teto de R$ 400 para o grupo.”

## Documentação

- [Instruções para agentes](AGENTS.md) e [guia da IA](docs/AI_GUIDE.md)
- [Estado do projeto](docs/PROJECT_STATE.md) e [continuidade](docs/CONTINUITY.md)
- [Privacidade](docs/PRIVACY.md), [testes](docs/TESTING.md) e [publicação](docs/RELEASING.md)
- [Contribuição](CONTRIBUTING.md), [segurança](SECURITY.md) e [histórico](CHANGELOG.md)

Não há serviço hospedado, integração obrigatória, credencial de instalação ou arquivos de viagens reais neste projeto.
