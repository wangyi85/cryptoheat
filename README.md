# **🎨 CryptoHeat NFT Market Place 🤖**

This template should help get you started developing with Svelte in Vite.

## **🧑‍🏭 User Actions**

- Login to account (authentication access)
- Create a new item (Upload data + image)
- Fetch Nft items.

## **🛠️ Local setup 🖥️**

- Clone repository
- Install packages
- Start cryptoheat

## **Tech Stacks & Framework**

- **🍰 Frontend UI**
  - SvelteJs: UI Library 😃
  - TailwindCss: class-based 🎨 CSS style
  - Iconify: Icon library 👃
  - ViteJs: 🤔
  - Vitest: Testing 🧪
- **🍝 Backend & API 🌵**
  - MongoDB: Database 🪣
  - ExpressJs : API & routes 🔌
  - JWT authentication 🔏
  - Cloudinary: Image storage (cloud) 🧃

## Challenges & Observations

**Stores in `SvelteJs`**: The whole concept of external stores and states felt different at first. With expectations of using stores and states the same way I usually do in ReactJs and NextJs.

- **Passing functions as props**: Passing props in svelte components is required using the `export` keyword. I always had to declare arrow functions using the `let` keyword. Although I intentionally 🧐 avoided using the `dispatch` in Svelte.
