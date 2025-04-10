🔍 Análise de Requisitos do Cliente

📘 Requisitos Funcionais (O que o sistema deve fazer)

ID

Requisito

Prioridade

Observações

RF01

Exibir Splash Screen com botões de login e cadastro

Alta

Apenas na primeira abertura do app

RF02

Permitir que o usuário faça login/cadastro

Alta

Após login, redirecionar para a Home

RF03

Exibir na Home Page: último podcast escutado e lista de podcasts recentes

Alta

Deve ter botão “Ver todos” que leva à lista completa

RF04

Exibir seção de podcasts populares com botão "Ver todos"

Alta

A página deve conter categorias e mais podcasts

RF05

Permitir navegação entre telas (home, perfil, favoritos etc.)

Média

Bottom navigation com 4 abas principais

RF06

Exibir página individual do podcast com foto, botão de compartilhar e de salvar

Alta

Visual consistente com as demais páginas

RF07

Incluir um player funcional com minutagem, informações do episódio e controles padrão

Alta

Deve funcionar na tela do episódio

RF08

Exibir letras do episódio no rodapé, ou uma mensagem de ausência

Alta

Texto: “Este episódio não possui letras disponíveis.”

RF09

Permitir que o usuário favorite letras exibidas

Média

Letras devem ser clicáveis

RF10

O app deve manter o padrão visual e de cores do Figma

Alta

Alinhado ao design aprovado

📕 Requisitos Não Funcionais (Como o sistema deve se comportar)

ID

Requisito

Prioridade

Observações

RNF01

O app deve ser visualmente responsivo e seguir o padrão visual definido no Figma

Alta

Todas as telas devem respeitar o design

RNF02

O tempo de carregamento entre telas deve ser inferior a 2 segundos

Média

Boa performance na navegação

RNF03

O player deve continuar funcionando ao alternar entre abas

Alta

Experiência contínua de áudio

RNF04

O app deve manter os dados do usuário (último podcast, favoritos etc.) salvos

Alta

Mesmo após fechar e reabrir o app

🧠 Considerações Técnicas e de UX

Login Persistente: Usuário não deve precisar logar toda vez.

UX Focada em Descoberta e Continuidade: Facilitar retomada de episódios.

Acessibilidade: Letras dos episódios devem ser legíveis e acessíveis.

Fallback amigável: Mensagens claras caso não haja letras ou podcasts.

