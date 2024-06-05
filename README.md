# A BigCommerce / Next.js Proof of Concept

This project supports guided lab exercises to create a basic implementation of a Next.js storefront for BigCommerce.

## Prerequisites

* Node.js 18.17 or later

This storefront is built on Next.js 14.

## Getting Started

Copy the _starter_ branch.

```
pnpm create next-app@latest -e \
  https://github.com/CNanninga/bc-composable-int-nextjs/tree/starter \
  /path/to/working/directory
```

## Fresh Next.js Install

Next.js was installed with the following command:

```
pnpm create next-app@latest ./ --ts --tailwind \
  --no-eslint --no-app --no-src-dir \
  --import-alias '@/*'
```
