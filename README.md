# TropaLive

Plataforma independente de descoberta de criadores, participação comunitária e missões de contribuição genuína para a Twitch.

## Estado atual

MVP visual com dados fictícios para demonstração. Ainda não possui login real, dados persistidos ou conexão com a API da Twitch.

## Rodar no Windows

Instale Node.js LTS. No PowerShell, dentro desta pasta:

```powershell
npm install
npm run dev
```

Abra o endereço local mostrado pelo Vite (normalmente http://127.0.0.1:5173).

## Próximas etapas

1. Banco Supabase, autenticação e regras RLS.
2. OAuth Twitch e integração oficial com Helix API via backend.
3. Missões verificáveis, limites contra abuso e moderação.
4. Premium e pagamentos após revisão de segurança, termos e privacidade.

## Segurança e integridade

- Nunca inclua segredos em variáveis `VITE_*`, pois são expostas ao navegador.
- Segredos OAuth e chaves privilegiadas devem ficar no backend.
- Não haverá recompensa por deixar stream aberta, troca de lurks, follow-for-follow ou inflação artificial de métricas.
- XP será não monetário, não transferível e concedido por contribuições genuínas.

TropaLive é um projeto independente e não é endossado pela Twitch.
