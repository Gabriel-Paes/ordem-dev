# Módulo 3 — Persistência e Deploy

> "Você fechou o terminal. Cadê as reservas?"

Neste módulo a API sai da sua máquina e vai para a internet.
Aprendemos a salvar dados de forma persistente e a publicar aplicações em produção.

## O que você vai aprender

- Por que dados em memória somem quando o servidor para
- Como salvar e recuperar dados com arquivos JSON
- O que é deploy e por que localhost não é suficiente
- Como publicar uma API gratuitamente no Render ou Railway

## Pré-requisitos

Conta no GitHub. Nenhuma instalação necessária além do Python.
Se quiser acompanhar o M2 antes: [Módulo 2](../module-2/README.md)

## Repositório de código

[api-cine — branch modulo-3](https://github.com/Gabriel-Paes/api-cine/tree/modulo-3)

Clone e rode em 3 comandos:

```bash
git clone -b modulo-3 https://github.com/Gabriel-Paes/api-cine
cd api-cine
pip install -r requirements.txt
uvicorn main:app --reload
```

Acesse: http://localhost:8000/docs

## Módulo anterior

← [Módulo 2 — APIs e Backend na Prática](../module-2/README.md)
