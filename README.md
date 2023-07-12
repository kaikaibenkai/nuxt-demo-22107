# Nuxt demo 22107

[issue](https://github.com/nuxt/nuxt/issues/22107)

Run:

```bash
$ pnpm dev
```

Visit:
- http://localhost:3000/app/file.txt -> OK, expected
- http://localhost:3000/file.txt -> OK, but **unexpected**, it should not exist
