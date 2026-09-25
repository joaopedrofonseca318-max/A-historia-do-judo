# 📘 Miniguia de Estudos com NotebookLM — A História do Judô

> Projeto desenvolvido como parte do desafio da [DIO](https://www.dio.me/), explorando o uso da Inteligência Artificial (NotebookLM) como ferramenta de aprendizagem ativa.

---

## 🎯 Contexto e Objetivos

**Assunto escolhido:** A história do Judo desde sua criação até a sua chegada ao Brasil e como esta funcionando atualmente.

**Por que escolhi esse tema:**
Esse tema foi escolhido pelo fato de eu ser um atleta e amante do esporte, e tendo em vista que é muito dificil achar fontes de conteudo sobre esse esporte em um só lugar sendo completo, decidi criar esse caderno para poder auxiliar tanto pessoas que buscam conhecimentos gerais como para os próprios atletas que buscam aprimoorar suas habilidades e conhecimentos.

**Objetivos de estudo:**
- [ ] Objetivo 1 — Dissertar sobre a historia do judo e de como ele chegou ao Brasil 
- [ ] Objetivo 2 — Gerar mapas mentais para cada grupo de tecnicas que sao necessarias aprendizado 
- [ ] Objetivo 3 — Criar prompts para poder ter uma breve iniciação de perguntas dentro do NotebookLM
- [ ] Objetivo 4 — Inserir um quiz de perguntas e respostas relacionadas ao conteudo do judo apresentado 

---

## 📚 Curadoria de Fontes

Fontes abertas (texto/PDF) selecionadas e carregadas no NotebookLM:

| # | Título da Fonte | Tipo | Link |

| 1 |CBJ - CONFEDERAÇÃO BRASILEIRA DE JUDO  | SITE  | https://cbj.com.br/pt/cbj/institucional |
| 2 |fIJ - FEDERAÇÃO INTERNACIONAL DE JUDO  | SITE  | https://www.ijf.org/history |
| 3 |CLASSIFICAÇÃO DE TÉCNICAS DE JUDO      | SITE  |https://judoinfo.com/gokyo3/|
| 4 | TUDO SOBRE JUDO  - TIME BRASIL TV     | VIDEO |https://www.youtube.com/watch?v=6LWfTDfOm7I |
| 5 | KYUSO MIFUNE E O LEGADO DO JUDO       | VIDEO |https://www.youtube.com/watch?v=k4qNSchw_4U |

***ESSAS SÃO SÓ ALGUMAS DAS 28 FOTES SELECIONADAS PARA FAZER PARTE DO NOTEBOOKLM***

**Critérios de seleção:** Forão selecionadas essas fontes com base nos meus conhecimentos de judo e de todas as coisas que aprendi durante minha carreira.
---

## 🧠 Engenharia de Prompts e "Cicatrizes"

Documentação do processo de perguntas feitas ao NotebookLM, variações testadas e aprendizados.

### Prompt 1
**Pergunta feita:**
QUAL A ORIGEM DO JUDO?

**Resposta obtida (resumo):**
O judô foi criado no Japão em **fevereiro de 1882** pelo educador e mestre **Jigoro Kano**. 

Os principais aspectos da origem do judô abrangem:

*   **Raízes no Jujutsu Clássico:** O judô é derivado das antigas escolas de *jujutsu* (arte marcial usada pelos samurais em combates desarmados), principalmente a **Tenjin Shin'yō-ryū** (focada em imobilizações e estrangulamentos) e a **Kitō-ryū** (especializada em projeções).
*   **A Motivação de Jigoro Kano:** Durante a juventude, Kano tinha uma constituição física frágil e sofria *bullying* de seus colegas. Para fortalecer seu corpo e aprender a se defender, ele decidiu estudar *jujutsu*.
*   **Fundação do Instituto Kodokan:** Aos 22 anos, Kano reuniu seus primeiros alunos e fundou seu próprio dojo no **Templo Budista Eishoji**, em Tóquio, espaço que mais tarde recebeu o nome de **Kodokan** ("lugar para estudar o caminho").
*   **Reforma Científica e Segurança:** Ao perceber que o *jujutsu* tradicional carecia de uma abordagem científica e envolvia técnicas muito perigosas, Kano eliminou os golpes fatais e reformulou os arremessos com base em leis da física e dinâmicas de desequilíbrio (*kuzushi*). Isso permitiu a prática livre e segura em força total (*randori*).
*   **Transição de "Jutsu" para "Do":** Para enfatizar que a modalidade não era apenas uma técnica de combate (*jutsu*), mas sim uma filosofia e um sistema educacional de desenvolvimento físico, mental e moral, Kano substituiu o sufixo por *Do* (caminho/via), batizando a arte de **Judô** ("Caminho Suave").
*   **Consolidação:** A eficiência do novo método foi comprovada publicamente em meados da década de 1880, quando os praticantes do Kodokan venceram desafios contra escolas tradicionais de *jujutsu* em torneios organizados pela Polícia Metropolitana de Tóquio.

💡 *Gostaria de explorar mais detalhes sobre como os princípios filosóficos de Jigoro Kano influenciaram a criação do judô ou saber como a modalidade se expandiu internacionalmente?*_

**Fontes citadas pela IA:**
A Brief History of Judo - Tri-City Jud
Historia do Judô: Da Defesa Pessoal e Combate ao Bullying ao Esporte Olímpico, Inspirado no Ju-Jutsu
O Legado Pedagógico, Filosófico e Técnico de Jigoro Kano: Gênese, Estruturação e Evolução do Judo Kodokan
History of Kodokan Judo
kodokan judo
CBJ | Confederação Brasileira de Judô
The Contribution of Judo to Education by Jigoro Kano

**Dificuldades / ajustes necessários:**
RESPOSTA BEM COMPLETA SEM A NECESSIDADE DE AJUSTES. 
---

### Prompt 2
**Pergunta feita:**
QUANTAS TECNICAS O JUDO POSSUI?

**Resposta obtida (resumo):**

O **Judô Kodokan** possui oficialmente **118 técnicas** (*waza*) catalogadas, que são distribuídas em três grandes categorias funcionais:

---

### 1. Nage-waza (Técnicas de Projeção / Arremesso) — **67 técnicas**
Utilizadas para desequilibrar e arremessar o oponente ao solo, dividindo-se em:
* **Tachi-waza** (Técnicas executadas em pé):
  * **Te-waza** (Técnicas de braço e mão): 15 técnicas
  * **Koshi-waza** (Técnicas de quadril): 11 técnicas
  * **Ashi-waza** (Técnicas de pé e perna): 21 técnicas
* **Sutemi-waza** (Técnicas de sacrifício, onde o praticante abre mão da postura ereta):
  * **Ma-sutemi-waza** (Sacrifício para trás): 5 técnicas
  * **Yoko-sutemi-waza** (Sacrifício lateral): 15 técnicas

---

### 2. Katame-waza (Técnicas de Domínio no Solo / Agarrame) — **29 técnicas**
Destinadas a imobilizar ou forçar a desistência do adversário:
* **Osaekomi-waza** (Técnicas de imobilização): 7 técnicas oficiais
* **Shime-waza** (Técnicas de estrangulamento): 12 técnicas
* **Kansetsu-waza** (Técnicas de chave articular no cotovelo): 10 técnicas

---

### 3. Atemi-waza (Técnicas de Golpes Traumáticos) — **22 técnicas**
Ataques diretos a pontos vitais do corpo. Devido ao alto risco de lesão, são estritamente proibidos no combate livre (*randori*) e em competições, sendo preservados exclusivamente no estudo dos *katas*:
* **Ude-ate-waza** (Golpes com os membros superiores — mãos, punhos e cotovelos): 16 técnicas
* **Ashi-ate-waza** (Golpes com os membros inferiores — joelhos, pés e calcanhares): 6 técnicas

---

Além do acervo oficial de 118 técnicas, o judô conta com o *Gokyo no Waza* (conjunto didático tradicional de 40 projeções do Kodokan), técnicas históricas preservadas (*Habukareta-waza*) e diversas variações e contra-ataques exercitados nas formas formais (*katas*).




**Fontes citadas pela IA:** 
Classification of Techniques in Kodokan Judo
Judo - Wikipedia
O Legado Pedagógico, Filosófico e Técnico de Jigoro Kano: Gênese, Estruturação e Evolução do Judo Kodokan

**Dificuldades / ajustes necessários:**
NÃO FORAM NECESSARIOS AJUSTES. _

---

### Prompt 3 (variação/refinamento)
**Pergunta feita:**
QUANTAS TECNICAS O JUDO POSSUI CONVENCIONALMENTE PARA EXAMES?


**O que mudou em relação à versão anterior:**
DEI UM CONTEXTO MELHOR PARA ELA SER MAISESPECIFICASOBRE DETERMINADO TOPICO. 

**Resultado:**]
A RESPOSTA SAIU MAIS COMPLETA E SEM SER APAGADA POR INFORMAÇÕES DESNECESSÁRIAS.



## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados

#### Conceito/Tópico 1
_[resumo estruturado, gerado com apoio do NotebookLM e revisado por você]_

#### Conceito/Tópico 2
_[resumo estruturado]_

#### Conceito/Tópico 3
_[resumo estruturado]_

---

### 2. Glossário

| Termo | Definição |
|-------|-----------|
|HISTÓRIA DO JUDO  | HISTÓRIA E CRIAÇÃO |
| TECNICAS E VARIAÇÕES  |CONJUNTO DE TECNIAS EXIXTENCES DO JUDO  |
| JIGORO KANO | HISTORIA DO CRIADOR DO JUDO  |

---

### 3. Prompts Reutilizáveis para Revisão Futura

Uma coleção de prompts testados e validados, prontos para reutilizar em revisões futuras:

```
1."QUAIS SAO AS PRINCIPAIS TECNICAS DA FAIXA LARANJA?"  

2. "CRIE UM QUIZ COM 10 PERGUNTAS RELACIONADAS A HISTOPRIA DO JUDO NO BRASIL."

3. "CITE 5 PRINCIPAIS DIFERENÇAS ENTRE O JUDO E O JIU JITSU."

4. "EXPLIQUE SOBRE A METODOLOGIA DE ENSINO DE JIGORO KANO."

5. "FAÇA UM SIMULADO DE EXAME DE NAGE NO KATA."


## 🛠️ Ferramentas Utilizadas

- [NotebookLM](https://notebooklm.google.com/) — curadoria de fontes e geração de respostas contextualizadas
**- NOTEBOOK CRIADO: https://notebook.google.com/notebook/0e7ee36b-8274-4526-a417-d87b6b5f26c6**
- GitHub — versionamento e portfólio

---

## ✅ Conclusão

_Aqui está a reflexão final, com base no tema **História e Filosofia do Judô** (aliado ao aprendizado de uso do GitHub):

---

### ✅ Conclusão

Estudar a história e a filosofia do Judô usando o NotebookLM mudou a forma como eu enxergava a modalidade. Antes, meu contato com o Judô era quase só técnico — golpes, categorias, regras de competição. Ao organizar fontes sobre a trajetória de Jigoro Kano e os princípios de **Seiryoku Zen'yo** (máxima eficiência com o mínimo de esforço) e **Jita Kyoei** (prosperidade e benefício mútuo), percebi que o Judô nasceu como um projeto educacional e filosófico, não apenas como um esporte de combate. Isso reposicionou meu entendimento: cada golpe e cada regra têm uma lógica ética por trás, pensada para formar caráter, não só vencer um adversário.

Sobre usar a IA como ferramenta de estudo: o NotebookLM foi mais útil quando eu fazia perguntas específicas e ancoradas nas fontes — por exemplo, pedir para comparar como diferentes autores descrevem a evolução do Judô do Jiu-Jitsu tradicional trouxe respostas muito mais ricas do que perguntas genéricas como "o que é Judô". Também aprendi a desconfiar de respostas que pareciam completas demais e sempre voltar às fontes originais para confirmar — a IA organiza e conecta ideias bem, mas a checagem continua sendo responsabilidade minha.

Por fim, o processo de montar esse repositório também foi meu primeiro contato mais estruturado com o GitHub. Aprendi na prática o fluxo de criar um repositório, editar um README direto pelo navegador, escrever um commit com uma mensagem clara e entender por que isso importa: versionamento e documentação não são burocracia, são o registro do meu próprio raciocínio — algo que só percebi o valor real depois de documentar minhas próprias "cicatrizes" de prompt.




> Projeto entregue como parte do desafio **"Explorando IA para Estudos com NotebookLM"** da [DIO](https://www.dio.me/).
