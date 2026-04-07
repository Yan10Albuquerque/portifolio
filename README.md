# Template de Portfólio Profissional

Template de portfólio estático, pensado para apresentar projetos a recrutadores com foco em desenvolvimento web, especialmente Django e ecossistema Python.

## Arquivos

- `index.html`: estrutura principal da página
- `styles.css`: visual, layout responsivo e animações

## Como personalizar

1. Altere `Seu Nome`, descrição profissional e links de contato em `index.html`.
2. Substitua os projetos de exemplo pelos seus cases reais.
3. Atualize stack, métricas e posicionamento para refletir sua experiência.
4. Troque os links fictícios de GitHub, LinkedIn, currículo e demos.

## Estrutura sugerida para os seus projetos

Para cada projeto, tente manter:

- problema que você resolveu
- tecnologias usadas
- como você estruturou backend/frontend
- impacto gerado ou resultado esperado

## Uso com Django

Se quiser transformar este template em uma página dentro de um projeto Django:

- mova `index.html` para `templates/`
- mova `styles.css` para `static/`
- ajuste o link do CSS usando a tag `{% static %}`

## Próximo passo recomendado

Adicionar seus dados reais e publicar em uma hospedagem simples como Vercel, Netlify ou dentro do próprio projeto Django.
