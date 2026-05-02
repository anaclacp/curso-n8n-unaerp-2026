# Intermediário

Aqui entram os estudos para quem já consegue montar fluxos e quer entender melhor LLMs, documentação, agentes e ferramentas usadas em aplicações reais.

## Documentação como habilidade

Ler documentação é parte do trabalho. Quando você estuda uma biblioteca, plataforma ou modelo, a documentação oficial ajuda a entender limites, parâmetros, exemplos atualizados e boas práticas.

No universo de IA, isso é ainda mais importante porque ferramentas mudam rápido. Um tutorial pode ficar velho, mas a documentação costuma refletir melhor o comportamento atual da ferramenta.

> Mesmo que use IA para construir os projetos, algumas não tem acesso às últimas atualizações dos frameworks/bibliotecas que está usando, então ler a documentação oficial acaba agilizando o processo de desenvolvimento, porque você tem acesso a informações mais precisas e atualizadas.

Materiais:

- Hugging Face: https://huggingface.co/
- Documentação do Hugging Face: https://huggingface.co/docs
- Documentação do n8n: https://docs.n8n.io/
- Cursos da Anthropic: https://anthropic.skilljar.com/

## Entendendo agentes

Antes de ir para papers e artigos mais densos, vale entender a ideia geral: um agente é um sistema que usa um modelo de linguagem para decidir próximos passos, chamar ferramentas, consultar contexto e produzir uma resposta ou ação.

Nem todo fluxo com IA precisa ser um agente. Muitas vezes, um workflow bem definido é melhor: ele é mais previsível, mais fácil de testar e mais simples de manter. Agentes fazem mais sentido quando o problema exige adaptação, escolha de ferramentas ou raciocínio em múltiplas etapas.

Conceitos importantes:

- Workflow: sequência mais previsível de passos, com começo, meio e fim bem definidos.
- Agente: sistema que pode decidir quais ações tomar dentro de um conjunto de possibilidades.
- Tool: função, API ou recurso externo que o modelo pode acionar para fazer algo.
- Contexto: informações entregues ao modelo para orientar a resposta.
- Memória: forma de guardar informações úteis entre interações.
- RAG: técnica para buscar informações externas e entregar esse contexto ao modelo.

Perguntas para guiar o uso:

- Esse problema precisa mesmo de um agente ou um workflow resolve melhor?
- Quais decisões o modelo deve tomar?
- Quais partes precisam ser determinísticas?
- Quais ferramentas o agente pode usar?
- Como vou avaliar se a resposta ou ação foi boa?

## Bancos de dados vetoriais

Bancos vetoriais são úteis quando você quer buscar informação por significado, e não apenas por palavras exatas. Eles aparecem em projetos com RAG, busca semântica, memória de agentes e recomendação.

Recomendações:

- Qdrant: https://qdrant.tech/
- Supabase Vector: https://supabase.com/vector

## Práticas recomendadas

- Monte um fluxo no n8n que recebe uma pergunta e busca contexto antes de chamar o modelo.
- Teste uma base pequena de documentos com embeddings.
- Compare respostas com e sem contexto externo.
- Crie um fluxo simples com uma ferramenta externa e observe quando a IA precisa ou não precisa usá-la.
- Antes de usar agente, tente desenhar o workflow ideal em passos.

