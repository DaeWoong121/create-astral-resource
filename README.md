# Create: Astral 한국어 리소스팩 (서버 배포용)

Create: Astral **v2.1.5b** (Minecraft 1.18.2 Fabric) 서버에서 접속자에게 자동으로 적용하는 한국어 리소스팩입니다.

- 번역 출처: 모루 (moru.gg) — `Create__Astral-2.1.5b-ko_kr-resource_pack.zip` + `overrides`의 `kubejs/assets` 번역을 하나로 합침
- 같은 키가 겹치면 overrides(KubeJS) 쪽 번역을 우선 적용

## 서버 설정 (server.properties)

```
resource-pack=https://raw.githubusercontent.com/DaeWoong121/create-astral-resource/main/Create_Astral-2.1.5b-ko_kr.zip
resource-pack-sha1=1479fab14fb9327eca931109ad5918c9df662fd4
```

zip을 바꾸면 `sha1sum`으로 새 해시를 구해서 `resource-pack-sha1`도 같이 바꿔야 합니다.

## 접속자

서버 접속 시 리소스팩 받기를 허용하고, 게임 언어를 **한국어**로 설정하면 됩니다.
