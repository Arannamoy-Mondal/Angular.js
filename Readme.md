# Install pnpm,yarn using dnf.
```bash
npm install -g corepack
corepack enable
corepack prepare pnpm@latest --activate
corepack prepare yarn@latest --activate
export SHELL=/bin/bash
pnpm setup
source ~/.bashrc
```

# Angular.js

```bash
pnpm add -g @angular/cli
```


# Project setup

```bash
ng new first-angular-app --no-zoneless
corepack use pnpm@latest
```