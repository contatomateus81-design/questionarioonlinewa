# Questionário Online — Yato

Página estática para levantamento técnico de requisitos de um site e sua hospedagem.

## Como funciona

- O visitante responde uma pergunta por vez.
- Ao final, revisa e pode editar as respostas.
- **Salvar** gera um link personalizado com as respostas codificadas no fragmento da URL (`#respostas=...`) e tenta copiá-lo para a área de transferência.
- **Enviar pelo WhatsApp** abre uma conversa com `+55 54 98129-6959` e preenche a mensagem completa com todas as respostas e o link personalizado.

## Privacidade e armazenamento

A página não possui backend nem banco de dados. As respostas ficam codificadas no próprio link; não são enviadas ao servidor do site. Qualquer pessoa que tenha o link poderá visualizar as respostas. O envio ao WhatsApp só ocorre após o visitante clicar no botão correspondente.

Não solicitar nem inserir senhas, documentos pessoais ou informações confidenciais neste questionário.

## Publicação

Projeto estático: basta publicar a raiz do repositório em um serviço de hospedagem de páginas estáticas, como Vercel ou GitHub Pages. Não há etapa de build nem variáveis de ambiente.
