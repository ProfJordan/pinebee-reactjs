# 🐝 Pinebee React Website
- Version: dev-2026.01.08

This is a **React + TypeScript + Vite** template designed using modern SaaS.

- Vite and HMR
- **Bootstrap 5**
- **React Router v6**
- TypeScript with ESLint rules

---

## 📦 Installation

```bash
git clone https://github.com/ProfJordan/pinebee-reactjs.git
cd pinebee-reactjs/pinebee-reactjs
npm install

## For local host -
- Open you command prompt
```bash
npm install or npm install --legacy-peer-deps
npm run dev (will start the dev server at http://loaclhost:5173)


## For locally build -
- Open you command prompt
- Open package.json file and edit scripts > build replace this "build": "next build && next export",
```bash
yarn build (will build locally and generate out folder in root directory)
yarn start (will start the locally build server at http://loaclhost:5173)

## Deploying to Vercel
- https://www.youtube.com/watch?v=_8wkKL0LKks


## Other Scripts
- Open you command prompt
```bash
yarn lint:fix
- (This will format your code and fix auto fixable eslint error)
