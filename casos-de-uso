# 📘 Casos de Uso – App de Podcast

---

## 📘 Caso de Uso 01 – Exibir Splash Screen com botões de login e cadastro

**Ator Principal:** Usuário  
**Pré-condição:** É a primeira vez que o app está sendo aberto  

### Fluxo Principal:
1. O usuário abre o app  
2. O sistema exibe a Splash Screen com os botões "Login" e "Cadastro"

### Fluxo Alternativo:
- **1A.** Se o usuário já estiver logado:  
  - O sistema ignora a Splash Screen e redireciona direto para a tela Home

**Pós-condição:** O usuário pode escolher entre login ou cadastro (se for novo)

---

## 📘 Caso de Uso 02 – Realizar Login/Cadastro

**Ator Principal:** Usuário  
**Pré-condição:** App instalado; acesso à internet  

### Fluxo Principal (Login):
1. O usuário clica em "Login"  
2. Insere e-mail e senha válidos  
3. Clica em "Entrar"  
4. O sistema valida os dados  
5. O sistema redireciona para a Home

### Fluxo Alternativo (Login):
- **2A.** Se o e-mail/senha estiverem incorretos:  
  - O sistema exibe uma mensagem de erro

### Fluxo Principal (Cadastro):
1. O usuário clica em "Cadastro"  
2. Preenche os dados e repete a senha  
3. O sistema verifica se os dados são válidos  
4. Cria a conta e redireciona para a Home

### Fluxo Alternativo (Cadastro):
- **2A.** Senhas não coincidem → erro exibido

---

## 📘 Caso de Uso 03 – Exibir conteúdo na Home

**Ator Principal:** Usuário autenticado  
**Pré-condição:** Login realizado  

### Fluxo Principal:
1. O usuário acessa a Home  
2. O sistema exibe:
   - Último podcast escutado  
   - Lista de podcasts recentes  
   - Botão "Ver todos"

### Fluxo Alternativo:
- **2A.** Se for uma conta nova:  
  - O sistema exibe mensagem: “Você ainda não ouviu nenhum podcast”

---

## 📘 Caso de Uso 04 – Acessar podcasts populares

**Ator Principal:** Usuário  
**Pré-condição:** Home aberta  

### Fluxo Principal:
1. O sistema exibe seção de podcasts populares  
2. O usuário pode clicar em "Ver todos" para abrir a lista completa

### Fluxo Alternativo:
- **1A.** Se a API não retornar dados:  
  - O sistema exibe a mensagem: “Nenhum podcast popular disponível”

---

## 📘 Caso de Uso 05 – Navegação entre telas

**Ator Principal:** Usuário  
**Pré-condição:** App aberto  

### Fluxo Principal:
1. O usuário clica em uma aba da bottom navigation (Home, Perfil, Favoritos)  
2. O sistema muda para a tela correspondente

### Fluxo Alternativo:
- **2A.** Se houver travamento:  
  - O app exibe erro ou impede navegação

---

## 📘 Caso de Uso 06 – Visualizar página individual do podcast

**Ator Principal:** Usuário  
**Pré-condição:** Home carregada  

### Fluxo Principal:
1. O usuário clica em um podcast  
2. O sistema exibe:
   - Imagem do podcast  
   - Botões de compartilhar e salvar  
   - Descrição do episódio  

---

## 📘 Caso de Uso 07 – Utilizar o Player

**Ator Principal:** Usuário  
**Pré-condição:** Episódio selecionado  

### Fluxo Principal:
1. O usuário clica em "Play"  
2. O player exibe:
   - Minutagem  
   - Nome do episódio  
   - Botões de controle (pausar, avançar, etc.)

### Fluxo Alternativo:
- **2A.** Se o usuário estiver offline:  
  - O sistema exibe mensagem de erro

---

## 📘 Caso de Uso 08 – Exibir letras do episódio

**Ator Principal:** Usuário  
**Pré-condição:** Player aberto  

### Fluxo Principal:
1. O sistema exibe letras sincronizadas no rodapé

### Fluxo Alternativo:
- **1A.** Se não houver letras:  
  - Exibir mensagem: “Este episódio não possui letras disponíveis.”

---

## 📘 Caso de Uso 09 – Favoritar podcast

**Ator Principal:** Usuário  
**Pré-condição:** Logado e com letra visível  

### Fluxo Principal:
1. O usuário clica no podcast  
2. O sistema salva como favorita

### Fluxo Alternativo:
- **1A.** Usuário não está logado:  
  - Exibe mensagem: “Faça login para favoritar”

---

## 📘 Caso de Uso 10 – Manter padrão visual

**Ator Principal:** Designer / QA / PO  
**Pré-condição:** App carregado  

### Fluxo Principal:
1. Verificar se telas seguem cores, fontes e estilos do Figma  
2. Garantir consistência de UI entre as páginas

