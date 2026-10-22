# Plano do portfólio de Rafael Oliveira

## Escopo

Reconstruir o portfólio pessoal como site estático, responsivo e editável, preservando a trajetória factual em Infraestrutura, Suporte, liderança técnica e consultoria, enquanto comunica de forma honesta a pós-graduação e a transição em andamento para Segurança da Informação.

## Design

**Estilos considerados:** terminal editorial sóbrio (0,06); dashboard cyberpunk neon (0,04); dossier executivo de operações (0,08).

**Escolha: dossier executivo de operações.**

- **Movimento:** editorial de tecnologia operacional, inspirado em painéis de observabilidade, relatórios de infraestrutura e documentação de engenharia.
- **Princípios:** clareza antes do efeito; evidência antes de adjetivos; contraste alto sem excesso de neon; experiência apresentada como linha de evolução.
- **Paleta:** fundo grafite quase preto para transmitir segurança e maturidade; azul elétrico para links e ações; verde sutil para status e resultados; branco quente para leitura.
- **Layout:** hero assimétrico com coluna de identidade e coluna de posicionamento; seções em faixas de conteúdo; timeline vertical compacta; cards com borda e indicadores, sem excesso de elementos centralizados.
- **Assinaturas:** marcador de status `// disponível para oportunidades`, micrograde técnica discreta e pequenos rótulos monoespaçados para categorias.
- **Interação:** navegação curta e previsível, scroll suave, cards com elevação mínima, menu mobile funcional e links de contato imediatos.
- **Animação:** entrada suave por seção e brilho mínimo no foco; sem pulsação permanente ou efeitos que prejudiquem a leitura.
- **Tipografia:** Manrope para títulos e corpo; IBM Plex Mono para metadados, tags e números de impacto.
- **Essência:** profissional de TI que transforma ambientes operacionais complexos em infraestrutura estável, documentada e preparada para evoluir em segurança. Personalidade: confiável, analítica, prática.
- **Voz:** objetiva, humana e baseada em fatos. Exemplos: “Infraestrutura que sustenta o negócio.” e “Experiência operacional aplicada à segurança.”
- **Marca:** monograma `RO/` como assinatura técnica, com nome em texto para acessibilidade.
- **Cor proprietária:** azul sinal `#62d8ff`, usado como fio visual entre operação e segurança.

## Implementação

- Site estático sem banco e sem servidor de aplicação.
- `index.html` com conteúdo completo no HTML inicial para SEO e acessibilidade.
- `styles.css` separado com responsividade para desktop, tablet e celular.
- `script.js` apenas para menu mobile, ano do rodapé e observação de elementos ao entrar na viewport.
- Foto existente `foto-rafael.jpg` reutilizada do site antigo.
- WhatsApp como link `https://wa.me/5547992425067`, abrindo em nova aba, com texto pré-preenchido.
- `public/manus-routes.json` declarando a rota `/`.
- Metadados de SEO e compartilhamento mantidos com o domínio antigo enquanto a publicação final não for conectada ao GitHub Pages.

## Estrutura

- `index.html`: estrutura e conteúdo público.
- `styles.css`: tokens visuais, componentes e breakpoints.
- `script.js`: interações leves.
- `foto-rafael.jpg`: foto reutilizada do portfólio antigo.
- `public/manus-routes.json`: manifesto de rotas.
- `app.config.ts`: logoUrl literal para o projeto.
- `plan.md` e `TODO.md`: decisões e progresso.
