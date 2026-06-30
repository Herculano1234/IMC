# Academia SG

Site estático otimizado para SEO, indexação no Google e publicação com domínio personalizado.

## O que está configurado
- Meta tags SEO, Open Graph e Twitter Cards
- Canonical URL e dados estruturados
- Sitemap XML e ficheiro robots.txt
- Página 404 personalizada
- Manifesto PWA básico
- Deploy automático para GitHub Pages
- Ficheiro CNAME para o domínio supergenius.co.ao

## Passos para publicar
1. Enviar o repositório para o GitHub.
2. Ativar GitHub Pages em Settings > Pages e escolher "GitHub Actions".
3. Configurar os registos DNS para supergenius.co.ao.
4. Adicionar o domínio em Settings > Pages.
5. Submeter o sitemap no Google Search Console.

## DNS recomendado
Para o domínio principal, usar registos A com os IPs do GitHub Pages:
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

E criar um registo CNAME para www se necessário.
