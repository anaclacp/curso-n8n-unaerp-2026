# Avançado

Esta trilha é para estudar os fundamentos técnicos por trás de LLMs, arquiteturas modernas e agentes. Alguns materiais são papers acadêmicos; não precisa entender tudo na primeira leitura.

## Como ler papers

- Leia primeiro o resumo, a introdução e as figuras.
- Procure a pergunta principal do paper: qual problema ele tenta resolver?
- Identifique a contribuição: o que mudou em relação ao que existia antes?
- Volte depois para detalhes matemáticos, experimentos e limitações.
- Faça uma anotação curta com: problema, ideia principal, resultado e dúvidas.

## Papers e leituras técnicas

- Attention Is All You Need, Vaswani et al. Paper que apresenta a arquitetura Transformer, base de muitos LLMs modernos: https://arxiv.org/abs/1706.03762 --> esse é o meu preferido, tem uma explicação passo a passo aqui: https://jalammar.github.io/illustrated-transformer/
- Building Effective Agents, Anthropic. Leitura essencial para diferenciar workflows previsiveis de agentes mais autonomos: https://www.anthropic.com/engineering/building-effective-agents
- Effective Context Engineering for AI Agents, Anthropic. Otimo para entender como contexto, ferramentas, memoria e instrucoes afetam o comportamento de agentes: https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents
- Building Agents with the Claude Agent SDK. Material mais pratico sobre construcao de agentes com SDK: https://claude.com/blog/building-agents-with-the-claude-agent-sdk

## Tópicos para aprofundar

- Transformers e mecanismo de atenção.
- Embeddings e similaridade vetorial.
- RAG e recuperação de contexto. (https://qdrant.tech/rag/) -> documentação que recomendo, bem completa e com exemplos.
- Tool use e function calling. (https://developers.openai.com/api/docs/guides/function-calling) -> documentação oficial da OpenAI, tem exemplos e boas práticas.
- Engenharia de contexto. 
- Avaliação de respostas de LLMs.
- Memória em agentes. (aqui você pode explorar diferentes abordagens, como memória de curto prazo (exemplo: por sessão), longo prazo (persistente em banco de dados, pode ser postgres, mongodb, banco vetorial -> framework recomendado: https://mem0.ai/),...)
- Observabilidade, custo e segurança em sistemas com IA. (existem vários frameworks e ferramentas para monitoramento, recomendações: langsmith que é diretamente para sistemas que envolvem IA...) 

## Práticas recomendadas

- Leia o paper dos Transformers com uma explicação complementar ao lado.
- Implemente um exemplo pequeno de busca semântica.
- Crie um agente com uma tool simples e registre onde ele acerta ou erra.
- Escreva seus próprios critérios de avaliação antes de comparar modelos ou prompts.

