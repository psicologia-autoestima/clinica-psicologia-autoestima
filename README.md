# Autoestima Psicologia - Manual Técnico e Documentação

Este documento contém as informações técnicas estruturais referentes ao site da clínica Autoestima Psicologia. Ele foi criado para garantir que a cliente tenha controle total sobre seus ativos digitais e para facilitar o trabalho de futuros desenvolvedores que possam atuar no projeto.

---

## 1. Informações Gerais do Projeto
* **Projeto:** Landing Page da clínica Autoestima Psicologia
* **Domínio Oficial:** psicologiaautoestima.com.br
* **Desenvolvedora Responsável:** Emilly Andrade - EA Soluções Digitais
* **Data de Entrega:** Agosto de 2026

---

## 2. Arquitetura e Tecnologias
O projeto foi construído focando em alta performance de carregamento e acessibilidade para alcançar notas máximas nos relatórios de auditoria (PageSpeed Insights).

* **HTML5 e CSS3:** Estrutura semântica e estilização limpa.
* **JavaScript Vanilla:** Interações nativas sem dependências pesadas. O carregamento utiliza o atributo `defer` para evitar bloqueio de renderização inicial.
* **Bootstrap 5:** Utilizado via CDN para o sistema de grid e componentes responsivos.
* **Lucide Icons:** Biblioteca de ícones carregada via CDN.
* **Integrações:** Google Tag Manager instalado no cabeçalho e iframe do Google Maps nativo.

---

## 3. Estrutura de Diretórios

```text
/assets
   /img                  # Imagens otimizadas em WebP
/css
   style.css             # Estilos customizados e variáveis de cor
/js
   main.js               # Inicialização de ícones (Lucide)
   navbar.js             # Comportamento de scroll do menu
   form-handler.js       # Lógica de envio para o WhatsApp
index.html               # Estrutura principal da página
robots.txt               # Regras para indexação em motores de busca
sitemap.xml              # Mapa do site para otimização de SEO