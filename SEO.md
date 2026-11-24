# Relatório de SEO — Sabores de Minas

## 1. Tema e palavras-chave

Tema do site: culinária mineira.

Palavras-chave principais trabalhadas:
1. **culinária mineira**
2. **pratos típicos mineiros**
3. **receitas tradicionais de Minas Gerais**

Na página `historia.html`, o foco específico é a história da culinária mineira, suas origens e tradições gastronômicas.

## 2. Decisões de otimização

| Recurso | Implementação |
|---|---|
| Title e meta description | Metadados exclusivos na página inicial e na página de história, com termos relacionados ao conteúdo de cada página |
| URL canonical | Uma URL canônica absoluta para cada página, usando o endereço publicado no GitHub Pages |
| Open Graph | `og:type`, `og:locale`, `og:site_name`, `og:title`, `og:description`, `og:url`, `og:image`, dimensões e texto alternativo |
| Imagem de compartilhamento | `imagens/og-sabores-de-minas.jpg`, em 1200 × 630 pixels |
| Favicon | `favicon.svg` vinculado nas duas páginas |
| Dados estruturados | `WebSite` na página inicial e `Article` na página de história, em JSON-LD |
| Robots | `robots.txt` na raiz, permitindo o rastreamento e apontando para o sitemap |
| Sitemap | `sitemap.xml` com as duas URLs absolutas do site |
| Links internos | Navegação descritiva entre a página inicial e `historia.html` |
| Imagens | Imagens de conteúdo convertidas para WebP, com `alt`, `width` e `height`; carregamento lazy nas imagens fora da primeira tela |
| Desempenho | Imagem principal priorizada e imagens abaixo da primeira tela carregadas sob demanda |

## 3. Tipos schema.org escolhidos

- **Página inicial:** `WebSite`, pois representa o site como um todo.
- **Página de história:** `Article`, pois apresenta um conteúdo informativo organizado como artigo.

Os blocos JSON-LD devem ser conferidos em https://validator.schema.org/.

## 4. Lighthouse — antes e depois

Executar o Lighthouse no Chrome com dispositivo **celular**, modo **navegação** e todas as categorias selecionadas. Registrar as notas reais dos relatórios. Não preencher valores estimados.

| Categoria | Antes | Depois |
|---|---:|---:|
| Desempenho | A preencher | A preencher |
| Acessibilidade | A preencher | A preencher |
| Boas práticas | A preencher | A preencher |
| SEO | A preencher | A preencher |

Meta solicitada na atividade para o resultado final:
- SEO: **95 ou mais**
- Acessibilidade: **90 ou mais**

## 5. Como registrar as medições

1. Publique as alterações no mesmo repositório do site.
2. Abra o site publicado no Chrome.
3. Pressione `F12` e selecione a aba **Lighthouse**.
4. Escolha **Navegação**, **Celular** e todas as categorias.
5. Gere e salve o relatório anterior e o relatório posterior às alterações (HTML ou captura de tela).
6. Transcreva as notas reais na tabela acima e mantenha os relatórios como evidência da atividade.

Também é possível medir o site publicado em https://pagespeed.web.dev/.

## 6. Observação

O projeto está configurado para o endereço `https://speedlx.github.io/saboresdeminas/`. Se o endereço de publicação mudar, atualize os campos `canonical`, Open Graph, JSON-LD, `robots.txt` e `sitemap.xml`.

//Utilizei o Gemini pra ajudar na relação do SEO com o arquivo. 