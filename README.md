# Plano Completo – Mês 1 de Programação

**Objetivo:** Recuperar a prática em HTML, CSS, JavaScript e React + terminar pelo menos 1 projeto sólido de portfólio.

**Perfil:** Motorista TVDE (tempo irregular)  
**Foco principal:** JavaScript + React + HTML/CSS  
**Tempo recomendado:** 1h30 a 2h por dia (pode ser dividido)

---

## Ferramentas a instalar no computador (faz isto primeiro)

1. **Visual Studio Code** → https://code.visualstudio.com
2. **Node.js** (versão LTS) → https://nodejs.org
3. **Git** → https://git-scm.com
4. Extensões no VS Code:
   - ES7+ React/Redux/React-Native snippets
   - Prettier
   - ESLint
   - Live Server
   - Auto Rename Tag
   - Path Intellisense

5. Contas a criar:
   - GitHub (https://github.com)
   - Vercel (https://vercel.com) – para publicar projetos

**Verificar instalação:**
Abre o terminal e escreve:
```bash
node -v
npm -v
git --version
```

---

## Prática no Telemóvel (tempos mortos)

Usa o telemóvel para **revisão e exercícios pequenos**. Projetos grandes faz no computador.

**Apps recomendadas:**
- **SoloLearn** → JavaScript, HTML, CSS (lições curtas)
- **Mimo** → Lições rápidas
- **Replit** (app) → Escrever e testar código
- **CodePen** (browser) → Testar HTML/CSS/JS rapidamente
- freeCodeCamp (no browser do telemóvel)

**Sugestão de uso:**
- 10–15 min entre viagens → 1 lição no SoloLearn/Mimo
- 15–20 min parado → Exercício pequeno no Replit ou CodePen

---

## Semana 1 – Revisão de HTML, CSS e JavaScript

### Dia 1
- HTML semântico (header, main, section, footer, nav)
- CSS básico + Flexbox
- **Exercício:** Página simples com cabeçalho, 3 secções e rodapé (tudo centrado com Flexbox)

### Dia 2
- CSS Grid
- Responsividade (media queries)
- **Exercício:** Tornar a página do Dia 1 totalmente responsiva (telemóvel + desktop)

### Dia 3
- JavaScript moderno: let/const, tipos, operadores, condicionais
- **Exercício:** Script que calcula lucro líquido de uma viagem TVDE (receita – combustível – comissão)

### Dia 4
- Funções, arrow functions, arrays e métodos (map, filter, reduce, find)
- **Exercício:** Lista de viagens fictícias → calcular total ganho, média e filtrar viagens acima de X euros

### Dia 5
- Objetos, destructuring, template strings
- **Exercício:** Criar objeto “Motorista” com dados e métodos (adicionar viagem, calcular total do dia)

### Dia 6
- DOM: selecionar elementos, alterar conteúdo, eventos (click, input)
- **Exercício:** Página com formulário que mostra o cálculo de lucro em tempo real

### Dia 7 (Revisão)
- Repete os exercícios que mais custaram
- Cria repositório no GitHub chamado `revisao-mes-1`
- Faz commit de tudo o que fizeste

---

## Semana 2 – JavaScript avançado + Início do React

### Dia 8
- Async/Await + Fetch
- **Exercício:** Pedido a uma API pública (ex: JSONPlaceholder) e mostrar os dados na página

### Dia 9
- LocalStorage
- **Exercício:** Guardar as viagens do dia no navegador e mostrar quando a página reabre

### Dia 10
- Introdução ao React + criar projeto com Vite
- **Comando:**
```bash
npm create vite@latest meu-primeiro-react -- --template react
cd meu-primeiro-react
npm install
npm run dev
```
- **Exercício:** Contador simples com useState

### Dia 11
- Componentes, props e useState
- **Exercício:** Componente `ViagemCard` que recebe dados por props

### Dia 12
- useEffect básico
- **Exercício:** Quando a página carrega, mostrar uma mensagem ou carregar dados fictícios

### Dia 13
- Listas, keys e formulários controlados
- **Exercício:** Lista de viagens + formulário para adicionar nova viagem

### Dia 14 (Revisão)
- Junta tudo numa pequena app React de “Registo de Viagens TVDE”
- Publica no GitHub

---

## Semana 3 – Projeto Principal: Landing Page

**Tema sugerido:** Landing page relacionada com o teu mundo (ex: serviço para motoristas TVDE, lavagem de carros, gestão de ganhos, ou negócio local fictício).

### Dia 15
- Estrutura HTML completa (header, hero, serviços, sobre, contacto, footer)
- Definir cores e tipografia

### Dia 16
- Estilização com CSS (Flexbox/Grid)
- Hero section bem feita e impactante

### Dia 17
- Secção de serviços + “Como funciona”
- Tornar tudo responsivo

### Dia 18
- Formulário de contacto + validação básica com JavaScript

### Dia 19
- Animações simples (hover, transições)
- Polimento visual

### Dia 20
- Testar em telemóvel e desktop
- Corrigir problemas

### Dia 21
- Converter partes importantes para React (componentes reutilizáveis)  
  **OU** manter em HTML/CSS/JS puro (também serve perfeitamente para portfólio)

---

## Semana 4 – Finalizar + Segundo Projeto

### Dia 22 a 24
- Terminar a landing page
- Escrever um bom README no GitHub
- Publicar online no Vercel ou Netlify

### Dia 25 a 27
**Segundo projeto:** Calculadora de Ganhos TVDE (em React)
- Inputs: valor da viagem, % comissão, km, preço do combustível
- Mostra lucro líquido estimado
- Guarda histórico no LocalStorage

### Dia 28 a 30
- Polir os dois projetos
- Melhorar visual e README
- Organizar o GitHub
- (Opcional) Criar um site simples que mostre os teus projetos

---

## O que deves ter no final do Mês 1

- [ ] Confiança recuperada em HTML, CSS, JavaScript e React básico
- [ ] 1 Landing Page completa publicada online + GitHub
- [ ] 1 Aplicação React (Calculadora TVDE) publicada
- [ ] Hábitos de programação reativados
- [ ] Repositórios organizados no GitHub

---

## Dicas importantes

- Nos dias mais cansados faz só 45–60 minutos (revisão ou exercício pequeno).
- Usa os tempos mortos no carro para SoloLearn, Mimo ou podcasts.
- Faz commit no GitHub todos os dias (mesmo que o código esteja incompleto).
- Não tentes fazer o projeto grande só no telemóvel.
- O verdadeiro progresso vem de **construir**, não só de ver tutoriais.

---

## Próximos passos depois do Mês 1

- Mês 2: Mais 1–2 projetos + começar a criar perfil em plataformas de freelance
- Mês 3: Primeiros contactos com clientes e trabalhos pequenos

---

**Boa sorte!**  
Sê consistente. Mesmo 1h por dia bem feita durante 30 dias faz uma diferença enorme.

Qualquer dúvida, volta aqui e continua.  
Tu consegues.
