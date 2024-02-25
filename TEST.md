# remix-cloudflare-template

## 개발

로컬 서버에서 개발하는 방법은

```sh
npm run build && npm run start
```

npm run start로 해서 wrangler를 실행시킨다.

이러면 wrangler.toml 파일의 kv namespace를 사용할 수 있다.

wrangler.toml 파일에 있는 GITHUB_TOKEN은 개발서버일때도 필요하다.

```sh
[vars]
GITHUB_TOKEN=""
```

