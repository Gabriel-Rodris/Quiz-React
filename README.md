# Quiz React

Projeto de estudo em React e Vite. O jogador responde perguntas de programação, recebe feedback após cada resposta e vê a pontuação ao fim da rodada.

## Como executar

```bash
npm ci
npm run dev
```

Abra o endereço exibido pelo Vite. Para gerar a versão de produção, use `npm run build`.

## Onde está o código

- `src/context/quiz.jsx` usa Context e `useReducer` para controlar a etapa, a pergunta atual, a resposta escolhida e a pontuação.
- `src/components/` contém as telas de boas-vindas, pergunta e resultado.
- `src/data/questions.js` contém as perguntas da rodada.
