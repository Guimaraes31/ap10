# Apartamento 10

Site institucional e catálogo de imóveis da **Apartamento 10 — Consultoria imobiliária** (HTML + Tailwind).

Dados extraídos do site oficial [apartamento10.com.br](https://www.apartamento10.com.br/) — sem inventar informações.

## Conteúdo

- `index.html` — landing premium (loader, animações, galeria em carrossel)
- `imovel.html` — detalhe com galeria, lightbox e barra de obra
- `assets/banners/` — hero e banners oficiais (locais)
- `assets/imoveis/` — fotos do catálogo (locais)
- `data/imoveis.js` — base de imóveis (publicados no site oficial)
- `data/imoveis.json` — mesma base em JSON
- `data/empresa.json` — dados institucionais
- `logo.png` / `favicon.png` — identidade visual oficial

## Contato (dados reais)

- Telefone / WhatsApp: (11) 99742-2540
- WhatsApp: (11) 99939-6202
- E-mail: contato.apartamento10@gmail.com
- Endereço: Rua Vilela, 652 · Tatuapé · São Paulo/SP · CEP 03314-000
- CRECI: 35397
- Instagram: [@apartamento10_](https://www.instagram.com/apartamento10_/)
- Facebook: [apartamento10](https://www.facebook.com/apartamento10)

## Catálogo atual

No momento da geração, o site oficial publicava **1 lançamento ativo**:

| Código | Nome | Local | Fase |
|--------|------|-------|------|
| 10027 | ANALIA FRANCO | Guaiaúna · São Paulo/SP | 75% pronto (Em obras) |

Valores: sob consulta (não publicados no site de origem).

## Como rodar

```bash
python3 -m http.server 8080
```

Abra `http://localhost:8080`.

## Referência de layout

Estrutura e UX baseadas no projeto `imobilia` (Nilde Imóveis), com identidade visual adaptada à marca Apartamento 10 (preto + dourado).
