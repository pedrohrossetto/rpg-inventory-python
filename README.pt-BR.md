*[Read in English](README.md)*


# rpg-inventory-python

Sistema de missões e inventário de um pequeno RPG ("Ecos de Arcadia") em Python, desenvolvido ao longo
da disciplina de Técnicas de Orientação a Objetos (IFSul, Ciência da Computação). Faz parte do meu repositório de [estudos](https://github.com/pedrohrossetto/studies).

## Conceitos praticados

- Encapsulamento com properties (`Missao`, `Personagem`, `Item`)
- Herança: missões de coleta, combate e exploração (`MissaoColeta`, `MissaoCombate`, `MissaoExploracao`)
- **Padrão State** para o status da missão: pendente → em andamento → concluída (`status.py`)
- Fábrica de missões (`factory.py`)

## Como rodar

```bash
cd src
python main.py          # demonstração
python teste_rpg.py     # testes de missões
python teste_itens.py   # testes de inventário
```
