# Strapi-to-TypeScript

Convert the Strapi models to TypeScript interfaces by processing each of the `./api/**/models/*.settings.json` recursively.

# Install and Run

```console
npm install -g strapi-to-typescript
sts path/to/strapi/api/ -o path/to/your/types/dir/
```

# Build

```console
npm i
npm run start
```

## Explanation

The input folder is recursively processed and each model file is read. When done, the expected output folder is generated, and finally, the Strapi models are converted to TypeScript.
