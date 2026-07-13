# Site — Dr. Pablo Luiz

Landing page do Dr. Pablo Luiz — medicina dedicada ao tratamento da obesidade e do emagrecimento.
Site estático (HTML/CSS/JS), sem build e sem dependências. Basta hospedar os arquivos.

## Estrutura

```
site-dr-pablo-luiz/
├── index.html                  # a página (edite textos aqui)
├── vercel.json                 # configuração da Vercel (cache/headers)
├── .gitignore
└── assets/
    ├── favicon.svg             # ícone da marca (aba do navegador)
    ├── og-image.png            # imagem de compartilhamento (WhatsApp, Instagram, Facebook)
    └── dr-pablo.jpg            # foto do Dr. Pablo (hero + seção "Sobre")
```

## O que já está pronto

- **Paleta verde-escura + dourado** (fundo escuro, conforme solicitado).
- **Foto real** do Dr. Pablo aplicada no hero e na seção "Sobre".
- **Calculadora de IMC** interativa (faixas de referência da OMS) com CTA para o WhatsApp.
- **WhatsApp** (86) 9 9957 5923 no header, botão flutuante e CTA final.
- **Instagram** @pabloluiz_nutrologia.

## Antes de publicar — 2 passos

1. **Domínio na imagem de compartilhamento:** no `index.html`, troque `https://SEU-DOMINIO.vercel.app`
   nas tags `og:image` / `twitter:image` pelo domínio real depois do deploy.
2. **Foto (opcional):** para trocar a foto, substitua `assets/dr-pablo.jpg` mantendo o mesmo nome.

## Publicar no GitHub

```bash
cd site-dr-pablo-luiz
git init
git add .
git commit -m "Site Dr. Pablo Luiz"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/site-dr-pablo-luiz.git
git push -u origin main
```

## Associar à Vercel

1. Acesse **vercel.com** e faça login com a conta do GitHub.
2. **Add New → Project** e selecione o repositório `site-dr-pablo-luiz`.
3. Framework Preset: **Other** (site estático). Build Command e Output vazios — a Vercel serve os arquivos como estão.
4. Clique em **Deploy**. Em segundos o site estará no ar em `https://site-dr-pablo-luiz.vercel.app`.
5. Para domínio próprio: **Settings → Domains** e aponte o seu domínio.

Cada `git push` na branch `main` publica a nova versão automaticamente.

## Conformidade (CFM)

Nome completo + CRM MG 102327 sempre visíveis. Sem superlativos, sem promessa de resultado, sem
antes/depois. Atuação descrita como "médico dedicado ao tratamento da obesidade e do emagrecimento".
A calculadora de IMC traz aviso explícito de que é orientação inicial e não substitui a consulta médica.
Base: Resolução CFM nº 1.974/2011.
