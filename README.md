# Engenharia de prompts para estudos

Repositório criado para o desafio prático da DIO, com o objetivo de usar a Inteligência Artificial (NotebookLM) como uma ferramenta para acelerar e melhorar os estudos.

🔗 **Acesse o meu Caderno no NotebookLM:** [Clique aqui para acessar]((https://notebooklm.google.com/notebook/861a65e9-cfb1-4fd7-ae7b-1230feedea97?authuser=1))

---

## 🎯 Contexto e Objetivos

* **Assunto:** Como criar bons prompts (comandos) para a IA ajudar na hora de estudar, sem que ela entregue textos genéricos ou invente informações.
* **Objetivos com esse projeto:** 
  1. Entender como "conversar" com a máquina de um jeito mais claro.
  2. Aprender a evitar as alucinações (quando a IA inventa dados falsos).
  3. Montar uma lista de comandos prontos para eu usar no dia a dia.

---

## 📚 Fontes Utilizadas

Para ensinar o NotebookLM sobre o assunto, selecionei as seguintes fontes gratuitas (um artigo em PDF e vídeos do YouTube importados pelo próprio link):

1. **[Artigo IBM] O que é Engenharia de Prompts?** - Texto explicativo sobre o básico dos comandos e como evitar respostas inventadas. (Link: https://www.ibm.com/br-pt/think/topics/prompt-engineering)
2. **[Vídeo] Aula Prática de Prompts 1** - Dicas visuais e exemplos de como pedir coisas para a IA. (Link: https://www.youtube.com/watch?v=1VDcke66TRE)
3. **[Vídeo] Aula Prática de Prompts 2** - Continuação das aulas práticas para melhorar respostas. (Link: https://www.youtube.com/watch?v=ATp4Q4UD-c8)
4. **[Vídeo] Aprimorando seus prompts (Guanabara)** - Aula excelente mostrando como organizar respostas em tabelas. (Link: https://www.youtube.com/watch?v=HQrvL2uBRGA)
5. **[Vídeo] Aula Prática de Prompts 3** - Explica o método "PROMPT" do Bruno Picinini para organizar ideias. (Link: https://www.youtube.com/watch?v=_3lq1Mg4lYw)

---

## 🛠️ Meus Testes e Ajustes (Cicatrizes)

Durante a criação deste guia, fiz testes no NotebookLM para ver como ele reagia a diferentes formas de pedir a mesma coisa.

| Tentativa | O que eu digitei (Prompt) | O que a IA respondeu | O que eu aprendi (Ajuste) |
| :--- | :--- | :--- | :--- |
| **01 (Comando solto)** | *"Resuma os vídeos e me explique o que é engenharia de prompt."* | Me entregou um texto gigante e super detalhado. Falou sobre a "regra de ouro", listas JSON e até explicou o método do Bruno Picinini. | **O erro:** A resposta estava correta, mas longa demais. Eu não disse qual era o tamanho que eu queria. Aprendi que a IA precisa de limites. |
| **02 (Ajuste de limite)** | *"Faça a mesma coisa, mas resuma em apenas um parágrafo curto."* | Ela resumiu, mas o texto ficou um pouco robótico e perdeu algumas informações importantes que eu queria guardar. | **O erro:** Limitei muito o tamanho, mas esqueci de pedir um formato visualmente bom para estudar. |
| **03 (Comando ideal)** | *"Aja como um professor. Resuma as 3 melhores dicas dos vídeos sobre como criar bons prompts. Formate a resposta em uma lista com marcadores."* | Resposta perfeita. O texto ficou fácil de ler, direto ao ponto e bem separado para eu revisar depois. | **Acerto:** Quando eu dou um papel (professor) e escolho o visual da resposta (lista), a IA funciona muito melhor. |

---

## 🚀 Meu Guia de Estudos 

### 📝 Resumo do que aprendi
Com base nas fontes, aprendi que engenharia de prompt é simplesmente a arte de dar boas instruções. Se uma pessoa não entenderia o seu pedido, a IA também não vai entender (essa é a Regra de Ouro).

Para não errar mais, anotei essas três dicas principais:
* **Siga o método PROMPT:** Defina a **Persona** (quem a IA deve ser), o **Roteiro** da tarefa, o **Objetivo**, o **Modelo** de saída (lista, tabela), o **Panorama** (o contexto) e peça para **Transformar** se não ficar bom.
* **Inversão de papéis:** Uma dica muito legal é pedir para a IA te fazer perguntas antes de ela começar o trabalho, para garantir que ela tem todas as informações que precisa.
* **Corte a criatividade quando necessário:** Para evitar informações falsas, sempre escreva no comando: *"Se você não souber a resposta, apenas diga que não sabe, não invente"*.

### 📖 Pequeno Glossário

* **Prompt:** É o comando, a frase ou a pergunta que você digita para a IA.
* **Alucinação:** É o nome que damos quando a inteligência artificial "viaja" e inventa uma resposta que não é verdade, fingindo que é.
* **Persona:** É o papel que você pede para a IA assumir (ex: "Aja como um programador" ou "Aja como um professor de matemática").

### 🔁 Comandos Prontos para Usar nos Estudos

Deixei esses três comandos salvos para copiar e colar sempre que eu for estudar um assunto novo:

1. **Para entender temas difíceis:** *"Aja como um professor paciente. Me explique o conceito de [COLAR O ASSUNTO] como se eu tivesse 12 anos. Use uma comparação com algo do dia a dia."*
2. **Para revisar antes de uma prova:** *"Baseado nos textos que te enviei, crie 5 perguntas de múltipla escolha para testar meu conhecimento. Me diga as respostas só depois que eu tentar adivinhar."*
3. **Para resumir textos longos:** *"Leia este texto e crie um resumo dividindo as informações em três tópicos principais, usando uma linguagem bem simples."*
