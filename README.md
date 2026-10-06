# Rise Agency — site completo

Versão de 6 de outubro de 2026, com todas as alterações da prévia local.

## Rodar no computador

Instale Node.js 22.13 ou superior e npm. Abra o terminal nesta pasta e execute:

```sh
npm ci
npm run dev
```

Acesse http://127.0.0.1:5173.

Para verificar o código e gerar uma versão de produção:

```sh
npx tsc --noEmit
npm run build
```

## Conteúdo incluído

- Código React/TypeScript, estilos, configurações e dependências registradas no package-lock.json.
- Logos em PNG transparente e imagens na pasta public.
- Relatório de tráfego pago animado conforme a rolagem.
- Contadores de resultados que reiniciam ao voltar à seção.
- Temak House na etapa 02, com animação do molho, três unidades e botão para o Instagram de Orlando.
- Resultados na etapa 03 e sequência de seções atualizada.
- Botões de contato direcionados ao WhatsApp da Rise.
- Seção final com botão de WhatsApp, sem questionário ou banco de dados.
- Layout responsivo e suporte a preferência por movimento reduzido.

WhatsApp: https://wa.me/message/TGECUVN3HZRYO1
Instagram: https://www.instagram.com/temakhouseorlando/

## Estrutura

- app/page.tsx: conteúdo e seções principais.
- app/globals.css: estilos e layout responsivo.
- app/TrafficScene.tsx: relatório animado.
- app/ScrollMetric.tsx: contadores.
- app/TemakExperience.tsx: cena e apresentação da Temak House.
- public/: logos e imagens.

As imagens gastronômicas são conceituais, não fotografias reais do restaurante. Os dados do relatório animado são ilustrativos; os resultados apresentados nas seções de cases foram informados pela Rise.

## Publicação

Este pacote contém o projeto atual em React/TypeScript com Vinext e configurações Sites/Cloudflare. Não é um único index.html que abre com duplo clique. Para GitHub + Vercel, ainda é necessário adaptar e testar a estrutura para Next.js padrão; este pacote não foi validado para deploy direto na Vercel. Nenhuma publicação foi confirmada.

O ZIP não inclui node_modules, caches, credenciais ou builds antigos. As dependências são instaladas com npm ci. Todos os arquivos de código, assets e configurações necessários estão incluídos.
