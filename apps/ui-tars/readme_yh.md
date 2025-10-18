git clone https://github.com/bytedance/ui-tars-desktop.git

cd ui-tars-desktop

vim apps/ui-tars/src/main/store/validate.ts

vim apps/ui-tars/src/renderer/src/components/Settings/category/chat.tsx

pnpm run dev:ui-tars

cd apps/ui-tars

pnpm run build

vim ~/develop/ui-tars-desktop/node_modules/electron-vite/dist/index.mjs +151

vim ~/develop/ui-tars-desktop/node_modules/macos-alias/lib/create.js


