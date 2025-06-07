```bash
npm init -y
npm install typescript @types/node -D
npx tsc --init
npm install tsx -D
```

tsconfig.json

https://github.com/microsoft/TypeScript/wiki/Node-Target-Mapping

> node --version
> 22.15

{
"compilerOptions": {
"lib": ["ES2023"],
"module": "nodenext",
"target": "ES2023"
}
}

package.json

```bash
"scripts": {
"dev": "tsx watch src/http/server.ts"
},
```

```bash
npm install fastify
```
