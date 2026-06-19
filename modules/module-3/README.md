# Módulo 3 — Persistência e Deploy

> "Você fechou o terminal. Cadê as reservas?"

## O que você vai aprender

- Por que dados em memória somem quando o servidor para
- Como salvar e recuperar dados com arquivos JSON
- O que é deploy e por que localhost não é suficiente
- Como publicar uma API gratuitamente no Render ou Railway

## Pré-requisitos

Conta no GitHub. Nenhuma instalação necessária além do Python.
Se quiser acompanhar o M2 antes: [Módulo 2](../module-2/README.md)

## Material

- [Slides](./Ordem%20Dev%20%E2%80%94%20M%C3%B3dulo%203_%20Persist%C3%AAncia%20e%20Deploy.pdf)
- [PDF complementar — em breve]

## Repositório de código

[api-cine — branch modulo-3](https://github.com/Gabriel-Paes/api-cine/tree/modulo-3)

## Como rodar

```bash
git clone -b modulo-3 https://github.com/Gabriel-Paes/api-cine
cd api-cine
pip install -r requirements.txt
uvicorn main:app --reload
```

Acesse: http://localhost:8000/docs

## Módulo anterior

[Módulo 2 — APIs e Backend na Prática](../module-2/README.md)

## Próximo módulo

[Módulo 4 — Frontend + Integração](../module-4/README.md)
