

# next-template

A Next.js 13 template for building projects with:

- React
- Typescript
- TailwindCSS
- shadcn-ui
- React-hook-form
- React-query
- Zod

## Initialize project

1.  Initialize project
```
npx create-next-app example --ts --tailwind --eslint --app --src-dir 
```

2. Initialize shadcn-ui
```
npx shadcn-ui@latest init
```

```
Would you like to use TypeScript (recommended)? yes
Which style would you like to use? › Default
Which color would you like to use as base color? › Neutral
Where is your global CSS file? › src/app/globals.css
Do you want to use CSS variables for colors? › yes
Where is your tailwind.config.js located? › tailwind.config.ts
Configure the import alias for components: › @/components
Configure the import alias for utils: › @/lib/utils
Are you using React Server Components? › yes

```

3. Install dependencies
```
npm i framer-motion jotai react-hook-form react-query zod
```

## Project structure

```
.
├── src/
│   ├── app/
│   │   ├── (api)/
│   │   │   └── api/
│   │   │       └── example/
│   │   │           └── route.ts
│   │   ├── (dashboard)/
│   │   │   ├── example/
│   │   │   │   └── page.tsx
│   │   │   ├── layout.tsx
│   │   │   └── page.tsx
│   │   ├── (site)/
│   │   │   ├── example/
│   │   │   │   └── page.tsx
│   │   │   ├── layout.tsx
│   │   │   ├── page.tsx
│   │   │   └── template.tsx
│   │   ├── (studio)/
│   │   │   ├── admin/
│   │   │   │   └── [[...index]]/
│   │   │   │       └── page.tsx
│   │   │   └── layout.tsx
│   │   ├── layout.tsx
│   │   └── globals.css
│   ├── components/
│   │   ├── ui/
│   │   │   ├── button.tsx
│   │   │   ├── form.tsx
│   │   │   ├── input.tsx
│   │   │   └── label.tsx
│   │   └── example-form.tsx
│   ├── hooks/
│   │   └── use-example.ts
│   ├── lib/
│   │   └── utils.ts
│   ├── types/
│   │   └── index.d.ts
│   └── sanity/
│       ├── config/
│       │   ├── client-config.ts
│       │   ├── desk-structure.ts
│       │   └── sanity.confit.ts
│       └── schemas/
│           ├── example/
│           │   ├── example.ts
│           │   └── index.ts
│           └── index.ts
└── public
```

## Where find ui components and how to use them?

#### Already made components (recommended):
- [ui.shadcn.com](https://ui.shadcn.com/docs/components)
- [radix-ui.com](https://www.radix-ui.com/themes/docs/overview/getting-started) | [GitHub](https://github.com/radix-ui/themes/tree/main/packages/radix-ui-themes/src/components)

#### Own components:
- [how to create own components using radix-ui](https://www.freecodecamp.org/news/unstyled-ui-components-for-front-end-developers#sample-code-from-radix-)
