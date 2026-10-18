# 🖋️ RAZA13 | Tattoo Studio — Landing Page

Landing Page institucional e comercial desenvolvida sob medida para o **RAZA13 Tattoo Studio**, estúdio especializado em tatuagens artísticas e body piercing localizado no bairro Cristo Rei em Várzea Grande – MT.

O projeto foi concebido para transformar a presença digital do estúdio em uma ferramenta ativa de atração e conversão de clientes, reunindo portfólio visual imersivo, localização física integrada e canal direto de orçamentos via WhatsApp.

🔗 **Acesse o projeto online:** [https://wagnercampos5.github.io/raza13-landing-page/](https://wagnercampos5.github.io/raza13-landing-page/)

---

## 📌 Sumário
- [Visão Geral](#-visão-geral)
- [Funcionalidades Principais](#-funcionalidades-principais)
- [Stack Tecnológica](#-stack-tecnológica)
- [Processo de Desenvolvimento e Engenharia](#-processo-de-desenvolvimento-e-engenharia)
- [Otimizações de SEO Local](#-otimizações-de-seo-local)
- [Autor](#-autor)

---

## 👁️ Visão Geral

O estúdio precisava de uma página que refletisse sua identidade estética marcante (dark/gothic/underground), ao mesmo tempo em que oferecesse velocidade de carregamento, navegação mobile impecável e eliminação de atritos para o cliente solicitar um orçamento.

A landing page substitui cardápios estáticos e links soltos em redes sociais por uma experiência centralizada de alta conversão.

---

## ✨ Funcionalidades Principais

* **Hero Section com Identidade Visual Marcante:**
  * Logotipo personalizado com efeito parallax e textura ao fundo.
  * Slogan oficial da marca (*"Modifique seu corpo, modifique sua alma!"*).
  * Selos destacados com todas as especialidades do tatuador: Realismo (Preto e Cinza), Oriental (Tradicional, Moderno, Neo), Neo Tradicional (P&B e Colorido), Aquarela, Blackwork, From Hell, Full Color, Lettering e Coberturas (Cover-up).
  * Chamada para ação (CTA) imediata para solicitação de orçamento.

* **Seção de Especialidades & Biossegurança:**
  * Cards modulares destacando técnicas de Blackwork & Fineline, Tatuagem Colorida e Body Piercing em titânio com grau cirúrgico.

* **Galeria Dinâmica com Modal Lightbox:**
  * Exibição de 23 trabalhos fotográficos em grid balanceada com carregamento sob demanda (`loading="lazy"`).
  * Efeito **Lightbox personalizado em Vanilla JavaScript**: ao clicar em qualquer miniatura, a imagem expande em resolução cheia sobre uma camada escura desfocada (`backdrop-filter`), permitindo fechar pelo botão `X` ou clicando no fundo.
  * Grid responsiva de duas colunas milimetricamente alinhada em ecrãs móveis sem quebra de viewport.

* **Agendamento com Orçamento Direto no WhatsApp:**
  * Formulário interativo (Nome, Telefone e Descrição da ideia).
  * Integração via script com a API do WhatsApp (`wa.me`), que formata automaticamente a mensagem em negrito e abre a conversa oficial do estúdio com os dados já preenchidos.
  * Tag de aviso explícita em vermelho: **"Só atendemos com hora marcada!"**.

* **Localização Física em Tempo Real (Google Maps):**
  * Mapa interativo embutido lado a lado com o formulário de orçamento, com alfinete exato no estúdio: *Rua Ary Paes Barreto, 2331 – Cristo Rei, Várzea Grande – MT*.

* **Rodapé e Identidade:**
  * Logo secundário do estúdio, ícones sociais interativos (Instagram e WhatsApp) estilizados em CSS e direitos reservados.
  * Favicon personalizado na aba do navegador.

---

## 🛠️ Stack Tecnológica

* **HTML5 Semântico:** Estruturação acessível com uso de tags `<header>`, `<nav>`, `<section>`, `<figure>`, `<footer>`.
* **CSS3 Moderno:**
  * Variáveis CSS globais (`:root`) para padronização de paleta de cores.
  * **CSS Grid** e **Flexbox** para layouts bidimensionais e alinhamentos simétricos.
  * Media Queries personalizadas com foco em abordagem *mobile-first*.
  * Efeitos de transição suave (`transition`), backdrop-filters e animações `@keyframes` no modal.
* **JavaScript (ES6+ Vanilla):**
  * Manipulação de DOM para o visualizador Lightbox.
  * Prevenção de envio padrão (`event.preventDefault()`) e codificação URI de parâmetros para o WhatsApp.
* **Bibliotecas & Recursos Externos:**
  * **Google Fonts:** Tipografia combinando *Cinzel* (títulos imponentes) e *Montserrat* (leitura fluida).
  * **FontAwesome 6:** Ícones vetoriais leves para redes sociais, horário e localização.
  * **Google Maps Embed API:** Iframe otimizado do ponto comercial.
* **Hospedagem & Deploy:**
  * **GitHub Pages** com controle de versão via Git e estratégia de *cache-busting* (`?v=x.x`) para atualização instantânea em clientes finais.

---

## ⚙️ Processo de Desenvolvimento e Engenharia

1. **Arquitetura e Layout:** Planejamento estrutural inspirado em referências de estúdios modernos, aplicando contraste alto (fundo preto `#0f0f0f` com acento vermelho escarlate `#e63946`).
2. **Resolução de Overflow Horizontal:** Ajuste fino de unidades flexíveis (`1fr`) e declarações estritas de `max-width: 100%` e `overflow-x: hidden`, eliminando barras de rolagem indesejadas no mobile.
3. **Refatoração da Galeria:** Correção de herança de tags duplicadas e normalização das margens padrão de `<figure>`, garantindo simetria absoluta em qualquer proporção de tela.
4. **Construção do Lightbox sem Dependências:** Implementação de modal leve em Vanilla JS, eliminando a necessidade de frameworks pesados (jQuery ou plugins externos) e mantendo a pontuação de performance alta no Lighthouse.
5. **Automação do Fluxo de Conversão:** Criação de script de ponte entre os campos do formulário e o protocolo URL do WhatsApp, garantindo que o lead chegue pronto para atendimento sem depender de backend de e-mail.

---

## 🔍 Otimizações de SEO Local

A página foi preparada para os motores de busca visando palavras-chave locais:
* Meta tags dedicadas para indexação no Google (`description`, `keywords`).
* Foco nos termos de busca: *"tatuagem varzea grande"*, *"estudio de tatuagem varzea grande"*, *"tattoo cristo rei"*.
* Meta tags Open Graph (`og:title`, `og:image`, `og:description`) configuradas para pré-visualização enriquecida ao compartilhar o link em WhatsApp, Instagram e Telegram.

---

## 👨‍💻 Autor

Projeto desenvolvido por **Wagner Julio de Campos**  
*Desenvolvedor Full Stack & Solopreneur*  
* Várzea Grande, MT - Brasil  
* LinkedIn: [@wagnercampos5](https://www.linkedin.com/in/wagnercampos5/)