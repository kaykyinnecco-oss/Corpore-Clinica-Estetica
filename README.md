# Córpore Clínica Estética

Site institucional responsivo da Córpore, em Santarém, desenvolvido com HTML, CSS e JavaScript, com Vite para desenvolvimento e build. Não precisa de backend, banco de dados ou variáveis de ambiente.

## Rodar localmente

Use Node.js 22.12+ ou 24 LTS.

```sh
npm ci
npm run dev
```

## Build de produção

```sh
npm run build
npm run preview
```

A pasta `dist` contém o site pronto para hospedagem.

## Publicar na Vercel

1. Acesse a Vercel e escolha **Add New → Project**.
2. Importe `kaykyinnecco-oss/Corpore-Clinica-Estetica` e selecione a branch `main`.
3. Mantenha o diretório raiz do repositório e o preset **Vite**.
4. Build: `npm run build`. Saída: `dist`. Instalação: `npm ci`.
5. Clique em **Deploy**. Não há variáveis de ambiente a cadastrar.

O arquivo `vercel.json` já registra o framework, comando de build e pasta de saída. Depois, o domínio pode ser configurado nas definições do projeto.

Referência oficial: https://vercel.com/docs/frameworks/frontend/vite

## Conteúdo e manutenção

- `index.html`: textos, seções, vídeos, mapa, Instagram e metadados.
- `style.css`: cores, fontes locais, layouts e versões responsivas.
- `main.js`: links de WhatsApp, ícone vetorial, menu móvel e controle de reprodução dos vídeos.
- `public/assets`: imagens e vídeos locais. Não dependem dos arquivos originais em Downloads.
- WhatsApp: `5593991436747`. Cada botão inclui uma mensagem contextual; o visitante confirma o envio no WhatsApp.
- Fontes: Cormorant Garamond e Manrope, servidas localmente pelo build via Fontsource.

As imagens editoriais de tratamentos foram geradas por IA e são ilustrativas. A logo, as fotos da clínica e da Dra. Marcela e os dois vídeos foram fornecidos pelo cliente. O primeiro vídeo corresponde ao Ultraformer 3, o segundo ao Laser Lavieen. Os textos dos procedimentos foram fornecidos pelo cliente. A apresentação da Dra. Marcela não acrescenta especialidades ou credenciais não informadas.

O mapa usa o iframe fornecido e depende do Google Maps. Os botões externos abrem em nova aba. Não há coleta de dados em formulário ou analytics próprio.

## Validação

Conferir build, imagens, navegação móvel, ausência de rolagem horizontal, reprodução dos dois vídeos e destinos dos links de WhatsApp. As capturas locais de revisão ficam em `qa/`, fora do Git.
