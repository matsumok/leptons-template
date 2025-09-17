# Leptos + Axum + Tailwindcss + daisyui Template

## WSL Git 設定
```bash
git config --global credential.helper "/mnt/c/Program\ Files/Git/mingw64/bin/git-credential-manager.exe"
```

## dev

```bash
npm run watch && cargo leptos watch
```

## Build
```bash
docker build -t leptos-app . 
docker run -d --name leptos-app -p 3000:8080 leptos-app
```


