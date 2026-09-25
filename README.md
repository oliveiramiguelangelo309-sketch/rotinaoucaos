# RoutineSync

Site estático para questionários de alimentação e produtividade.

## Arquivos

- `index.html` — telas do aplicativo
- `style.css` — estilos
- `questions.js` — perguntas dos questionários
- `app.js` — navegação, cálculo do resultado e plano personalizado

## Executar localmente

Sirva esta pasta com qualquer servidor estático (por exemplo, a extensão Live Server). O navegador precisa carregar `app.js` como módulo ES para resolver `questions.js`.

## Publicar

Envie estes arquivos para um repositório GitHub e importe o repositório na Vercel. Não é necessário comando de build: use a pasta raiz como diretório do projeto e deixe Build Command e Output Directory vazios (ou selecione Other/Static).

## Supabase

A versão atual não envia nem persiste respostas e não tem cadastro/login. Supabase só é necessário se você quiser guardar resultados, autenticar usuários ou administrar conteúdo. Não coloque chaves `service_role` no código do navegador.