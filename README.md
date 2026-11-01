# ☢️ Fallout RPG Toolkit

> Três ferramentas web para jogar e mestrar **Fallout RPG**, criadas por um fã de RPG de mesa com ajuda de **engenharia de prompt** e inteligência artificial.

![HTML](https://img.shields.io/badge/HTML-CSS-JavaScript-orange)
![Feito com IA](https://img.shields.io/badge/feito%20com-engenharia%20de%20prompt-green)
![Status](https://img.shields.io/badge/status-em%20evolu%C3%A7%C3%A3o-yellow)

---

## 📖 Sobre o projeto

Sou **João Pedro**, estudante de Análise e Desenvolvimento de Sistemas e apaixonado por RPG de mesa e pelo universo de **Fallout**. Este repositório nasceu de uma pergunta simples:

> *"E se eu pudesse transformar o livro de regras em ferramentas que eu e meus amigos realmente usamos na mesa?"*

Em vez de só pedir "faça um programa de Fallout", usei a IA como parceira de desenvolvimento, guiando cada etapa com prompts claros, o livro de regras como fonte da verdade e melhorias incrementais. O resultado são três ferramentas que conversam entre si.

---

## 🧰 As ferramentas

### 1. 📚 Guia de Atributos e Origens
**Arquivo:** `guia-atributos-origens-fallout.html`

Um guia interativo que apresenta como funcionam os atributos **S.P.E.C.I.A.L.**, explica todas as **origens** do jogo e detalha as **perícias**. Foi feito para quem está começando e precisa entender o sistema antes de montar a ficha.

### 2. 🧑‍🚀 Criador de Personagem
**Arquivo:** `criador-personagem-fallout.html`

Um assistente passo a passo para criar a ficha do personagem seguindo as regras do livro. Recursos:

- Criação guiada de personagem conforme o livro de regras
- Visual inspirado na estética do próprio livro
- Edição de **inventário**
- Sistema de **subir de nível**

### 3. 📟 Simulador de Pip-Boy 3000
**Arquivo:** `Pip-Boy-3000-Simulador.html`

Uma simulação do famoso dispositivo de pulso da série. Recursos:

- Abas no estilo do Pip-Boy, incluindo **DATA** e **RÁDIO**, em que o próprio jogador cadastra suas missões, notas e estações (nada vem pré-cadastrado)
- **Inventário** com adicionar, remover e editar itens
- Sistema de **armaduras** que afetam a defesa e podem modificar os atributos SPECIAL
- Aba **V.A.T.S.** com rolagens de dados usando o sistema do livro de regras
- **Integração com o Criador de Personagem**: os dados da ficha criada são carregados no Pip-Boy

```
Guia de Atributos  →  Criador de Personagem  →  Pip-Boy
   (aprender)            (criar a ficha)          (jogar)
```

---

## 🤖 Como usei engenharia de prompt

Este projeto foi construído em conversa com a IA, e a qualidade do resultado dependeu muito da **forma de pedir**. Estas foram as estratégias que usei:

### 1. Dar uma fonte da verdade
Anexei o **livro de regras em PDF** e pedi que os sistemas fossem feitos **com base nele**. Isso reduz o risco de a IA inventar regras e mantém as ferramentas fiéis ao jogo.

> *Exemplo de prompt:* "Faça um programa que faça a criação de personagem do RPG Fallout, com base no livro de regras anexado."

### 2. Começar simples e evoluir em camadas
Em vez de pedir tudo de uma vez, fui construindo por etapas:

1. Primeiro, o criador de personagem básico
2. Depois, a melhoria da estética com base no livro
3. Em seguida, o guia de atributos e origens
4. Então, a explicação das perícias
5. Por fim, inventário editável e sistema de nível

Cada rodada de prompt melhora o que já existe, o que facilita testar e corrigir.

### 3. Definir restrições claras
Deixei explícito o que **não** queria, para evitar resultado genérico:

> *Exemplo:* "Nas abas DATA e RÁDIO, não quero itens pré-cadastrados. Quero um sistema para o próprio usuário adicionar missões, notas e estações."

### 4. Pedir integração entre sistemas
Pensei nos projetos como um ecossistema, e não como programas isolados:

> *Exemplo:* "Quero vincular o Pip-Boy ao criador de personagem para carregar no Pip-Boy os dados da ficha criada."

### 5. Referenciar a estética e a identidade
Usei a identidade visual do livro e do jogo como referência de design, para que as telas tivessem o clima pós-apocalíptico de Fallout.

### 6. Pedir funcionalidades específicas e testáveis
Quando queria algo novo, descrevia o comportamento esperado, como a aba V.A.T.S. usando as rolagens do livro e as armaduras alterando defesa e SPECIAL. Isso facilita conferir se a IA entendeu o pedido.

### 7. Iterar, revisar e validar
A IA gera o código, mas eu testo, confiro com o livro e peço ajustes. Prompt bom é **conversa**, não pedido único.

---

## 🎲 Por que Fallout e RPG?

Sempre gostei de RPG de mesa: construir personagens, contar histórias e tomar decisões com os amigos. Fallout reúne tudo isso, com humor, sobrevivência, escolhas morais e um mundo cheio de personalidade.

Quando percebi que dava para transformar essa paixão em software, os projetos ganharam outro sentido. Cada ferramenta resolve uma dor real de quem joga:

| Problema na mesa | Solução |
|---|---|
| "Não entendi como funcionam os atributos" | Guia de Atributos e Origens |
| "Criar a ficha demora e é fácil errar" | Criador de Personagem |
| "Quero a imersão do Pip-Boy na mesa" | Simulador de Pip-Boy |

---

## 🚀 Como usar

Os projetos são arquivos **HTML** e rodam direto no navegador, sem instalação.

```bash
# 1. Clone o repositório
git clone https://github.com/jpcs120308-cpu/NOME-DO-REPOSITORIO.git

# 2. Abra o arquivo desejado no navegador
#    - guia-atributos-origens-fallout.html
#    - criador-personagem-fallout.html
#    - Pip-Boy-3000-Simulador.html
```

---

## 🛠️ Tecnologias

- HTML, CSS e JavaScript
- IA generativa como assistente de desenvolvimento
- Engenharia de prompt como método de trabalho

---

## 📸 Capturas de tela

> *Adicione aqui prints de cada ferramenta.*

| Guia de Atributos | Criador de Personagem | Pip-Boy |
|---|---|---|
| ![guia](docs/guia.png) | ![criador](docs/criador.png) | ![pipboy](docs/pipboy.png) |

---

## 🧠 O que aprendi

- Escrever prompts específicos, com contexto e restrições, muda completamente a qualidade da resposta
- Usar um documento como fonte da verdade deixa o resultado mais confiável
- Dividir um projeto grande em etapas pequenas facilita testar e corrigir
- A IA acelera o desenvolvimento, mas **revisar e entender o código continua sendo meu papel**

---

## 🗺️ Próximos passos

- [ ] Salvar fichas no navegador ou exportar em arquivo
- [ ] Integrar o Escudo do Mestre (regras, encontros aleatórios e loot)
- [ ] Melhorar a responsividade para celular
- [ ] Novas abas e funcionalidades no Pip-Boy

---

## ⚠️ Aviso

Este é um **projeto de fã**, sem fins lucrativos e sem afiliação com a Bethesda, a Modiphius ou os detentores oficiais de Fallout. O livro de regras **não está incluído** neste repositório. Fallout e todos os elementos relacionados pertencem aos seus respectivos proprietários.

---

## 👤 Autor

**João Pedro Camargo de Souza**
Estudante de Análise e Desenvolvimento de Sistemas
GitHub: [@jpcs120308-cpu](https://github.com/jpcs120308-cpu)

---

*"A guerra... a guerra nunca muda." Mas as nossas fichas agora podem evoluir.* ☢️
