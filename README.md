# Editor de código

### Repo de la Hackathon Del Dev

<img src="https://www.colabtools.online/code.png"  alt="Herramienta de colaboracion en linea)" />




#### Documentacion del proyecyto
- [Docs](https://docs.colabtools.online/)


### Estructura del proyecto

```
└── 📁code-colab_tools
    └── .gitignore
    └── .prettierrc
    └── README.md
    └── liveblocks.config.ts
    └── next.config.js
    └── package-lock.json
    └── package.json
    └── 📁public
        └── icon.svg
    └── 📁src
        └── 📁app
            └── Room.tsx
            └── 📁api
                └── 📁liveblocks-auth
                    └── route.ts
            └── layout.tsx
            └── page.tsx
        └── 📁components
            └── Avatars.module.css
            └── Avatars.tsx
            └── CollaborativeEditor.module.css
            └── CollaborativeEditor.tsx
            └── Loading.module.css
            └── Loading.tsx
            └── Toolbar.module.css
            └── Toolbar.tsx
        └── globals.css
        └── liveblocks.config.ts
    └── tsconfig.json
```

#### Comenzar:

#####  Clonar el repositorio:

```bash
git clone https://github.com/uprizingFaze/code-colab_tools.git
cd code-colab_tools
```

#####  Instalación de dependencias:


```bash
npm install
```

##### Ejectute el servidor de desarrollo:


```bash
npm run dev
# o
yarn dev
# o
pnpm dev
# o
bun dev
```
