# Katlen Ariane — Landing page profissional

Landing page responsiva integrada ao **V8 Admin Universal**.

- Projeto V8: `be844101-c846-491b-bcf8-87626d91cffe`
- API: `https://v8adminuniversal.aisermelk.workers.dev`
- Painel: `https://v8adminuniversal.pages.dev`
- Loader preservado: `js/v8-loader.js` (não foi alterado)
- Imagens originais preservadas em `assets/`
- CSS e interface responsivos em `css/style.css` e `js/main.js`

## Integrações

O V8 Loader carrega a configuração pública do projeto. O Pixel da Meta, Analytics, SEO dinâmico, redes sociais, WhatsApp, conteúdo, catálogo e scripts são geridos pelo V8 Admin Universal conforme a configuração habilitada no painel. Os botões principais possuem `data-v8-event="Contact"` para que o Loader registre o evento quando o Pixel estiver configurado.

A página não envia campos de saúde ou informações íntimas para o Pixel. Não inclua informações sensíveis em URLs, nomes de eventos, parâmetros ou formulários. Configure no painel apenas a medição necessária e os avisos/consentimentos de privacidade aplicáveis.

## Publicação no Cloudflare Pages

1. Extraia esta pasta e envie seu conteúdo ao repositório GitHub do site.
2. No Cloudflare Pages, use build command vazio e diretório de saída `/` (raiz do projeto).
3. Antes de substituir o site publicado, teste em uma implantação de pré-visualização.
4. Confirme no V8 Admin Universal se WhatsApp, redes sociais, catálogo e Pixel estão configurados corretamente.
5. Após definir domínio definitivo, atualize `canonical`, `og:url`, URLs de imagem e `sitemap.xml`.

## Observação importante

Nenhum layout ou configuração garante que um domínio ou Pixel não será restringido pela Meta. Esta página é uma apresentação transparente do serviço, não uma forma de ocultar o destino real do anúncio ou contornar revisão de políticas.
