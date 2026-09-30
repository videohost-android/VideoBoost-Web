# VideoBoost Web

Versão web responsiva criada a partir da interface do projeto Android.

## O que já funciona
- Login/cadastro usando `/api/auth/login` e `/api/auth/register`
- Dashboard usando `/api/operations/overview` e `/api/jobs`
- Listagem de vídeos e status
- Upload múltiplo para `/api/jobs`
- Configuração da URL da API
- Sessão salva no navegador
- Layout responsivo para celular e computador

## Importante sobre privacidade
O login real depende do backend/API. Esta pasta é o frontend; não coloque uma senha mestra dentro do JavaScript. Para publicar de forma privada, hospede o frontend e mantenha a API protegida por autenticação/HTTPS.

## Teste local
Abra `index.html` por um servidor HTTP local. Depois informe a URL do backend em Configurações ou na tela inicial.
