# vue2 + vite + tailwind boilerplate

This boilerplate works great for me.
I don't want to migrate to Vue3, because Vue2 is what I've invested much time into.
Vite keeps my build times low and tailwind is nice to use with Vue.

## How to dev

```bash
git clone --depth 1 https://github.com/MrYakobo/vue2-vite-tailwind
cd vue2-vite-tailwind
rm -rf .git
npm i
npm run dev # do your work in App.vue
```

## How to deploy

```bash
npm run build
scp -r dist/* my_server:/path/to/webroot/
```
