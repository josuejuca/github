---
name: Feature Request
about: Sugerir uma nova funcionalidade ou melhoria
title: "[feat] "
labels: ["feature"]
assignees: ""
---

## Descrição da funcionalidade
Descreva claramente a funcionalidade que você gostaria de ver implementada.

Exemplo:
> Criar endpoint para ativação de plano gratuito via API.

---

## Problema que resolve
Qual problema atual essa funcionalidade resolve?

Exemplo:
> Atualmente o usuário precisa ativar manualmente no banco, o que não é escalável.

---

## Solução proposta
Explique como você imagina que isso deveria funcionar.

- Endpoint `POST /api/v1/ativar-free/{usuario_id}`
- Atualiza campo `status = 10`
- Retorna JSON com novo status

---

## Alternativas consideradas
Você pensou em outra abordagem? Se sim, descreva aqui.

---

## Escopo
O que essa feature deve incluir?

- [ ] Backend
- [ ] Frontend
- [ ] Banco de dados
- [ ] Documentação
- [ ] Testes automatizados

---

## Critérios de aceite
A issue será considerada concluída quando:

- [ ] Funcionalidade implementada
- [ ] Sem quebrar rotas existentes
- [ ] Testada manualmente
- [ ] Documentada

---

## Contexto adicional
Inclua prints, exemplos de API, fluxos ou qualquer informação relevante.
