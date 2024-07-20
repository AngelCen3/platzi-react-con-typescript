# Curso de React.js con TypeScript

The first thing to do is: Use the command --> Curso de React.js con TypeScript
to create a new project with React

-Para que quede como en el proyecto de Jonathan
   -Would you like to use ESLint with this project? › Yes
   -Would you like to use src/ directory with this project? › No
   -Would you like to use experimental app/ directory with this project? › No

## Modific the file -> tsconfig.json

```bash
{
  "compilerOptions": {
    "lib": ["dom", "dom.iterable", "esnext"],
    "allowJs": true,
    "skipLibCheck": true,
    "strict": true,         //We make sure that strict: true    "noEmit": true,
    "esModuleInterop": true,
    "module": "esnext",
    "moduleResolution": "bundler",
    "resolveJsonModule": true,
    "isolatedModules": true,
    "jsx": "preserve",
    "incremental": true,
    "noImplicitAny": true,   //Does not allow ImplicitAny
    "noImplicitReturns": true,  //That not be able to ImplicitReturns
    "paths": {
      "@/*": ["./*"]
    }
  },
  "include": ["next-env.d.ts", "**/*.ts", "**/*.tsx"],
  "exclude": ["node_modules"]
```

## Modific the file -> .eslintrc.json

```bash
{
  "extends": "next/core-web-vitals",
  "rules": {            //Those modifications just we do to test this tutorial
    "@next/next/no-img-element": "off",     //AI: "We will only modify this for academic purposes on this occasion."
    "jsx-a11y/alt-text": "off"
  }
```
