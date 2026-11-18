# Three.js Adventure

Prototype 0.1 d’un Action-RPG isométrique en Three.js, SvelteKit et TypeScript.

## Gameplay prévu

- Exploration libre de régions interconnectées et donjons/tunnels guidés.
- Un héros contrôlé, compagnon IA, combats semi-automatiques.
- Creusement, collecte, missions et sauvegardes locales.
- Développement PC web d'abord, puis Android/iOS.

## État du dépôt

Ce dépôt a été initialisé. **Les sources du prototype ne sont pas encore publiées ici.** La dernière archive locale est `threejs-adventure-0.1-hud-visuals-tests.zip` dans la conversation de travail.

Après import des sources :

```bash
corepack enable
corepack prepare pnpm@10.15.1 --activate
pnpm install
pnpm dev
```

Le prototype reste en cours de validation : la compilation web et les tests navigateur n'ont pas encore été confirmés.
