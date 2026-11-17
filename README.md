*[Leia em português](README.pt-BR.md)*


# rpg-inventory-python

Quest and inventory system for a small RPG ("Ecos de Arcadia") in Python, built across the
Object-Oriented Programming Techniques course (IFSul, Computer Science). Part of my [studies](https://github.com/pedrohrossetto/studies) archive.

## Concepts practised

- Encapsulation with properties (`Missao`, `Personagem`, `Item`)
- Inheritance: collection, combat and exploration quests (`MissaoColeta`, `MissaoCombate`, `MissaoExploracao`)
- **State pattern** for quest status: pending → in progress → completed (`status.py`)
- Factory for creating quests (`factory.py`)

## Running

```bash
cd src
python main.py          # demo
python teste_rpg.py     # quest tests
python teste_itens.py   # inventory tests
```
