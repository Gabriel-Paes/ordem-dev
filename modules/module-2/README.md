# Módulo 2 — APIs e Backend na Prática

> Por que o site do ingresso.com caiu quando todo mundo tentou comprar o Homem-Aranha?

## O que você vai aprender

- HTTP e o ciclo de uma requisição
- Verbos REST: GET, POST, PUT, DELETE, PATCH
- Status codes: o que cada faixa significa
- FastAPI e documentação automática com Swagger
- Race condition na prática: quando dois pedidos chegam ao mesmo tempo

## Pré-requisitos

Conta no GitHub (para o Codespace). Nenhuma instalação necessária.

## Material

- [Slides](./Ordem%20Dev%20%E2%80%94%20M%C3%B3dulo%202_%20APIs%20e%20Backend.pdf)
- [PDF complementar — em breve]

## Repositório de código

[api-cine](https://github.com/Gabriel-Paes/api-cine) — Clone, rode e assista a API quebrar ao vivo.

## Como rodar

```bash
git clone https://github.com/Gabriel-Paes/api-cine
cd api-cine
pip install -r requirements.txt
uvicorn base.main:app --reload
```

Acesse http://localhost:8000/docs

## Módulo anterior

[Módulo 1 — Versionamento com Git](../module-1/README.md)

## Próximo módulo

[Módulo 3 — Persistência e Deploy](../module-3/README.md)
