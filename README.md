<div align="center">

<img src="https://pingy.top/assets/pingy-mark.svg" width="88" alt="Pingy" />

# Pingy VPN

**Клиент для VPN-подключения: лёгкая настройка, стабильная работа и контроль без лишней сложности.**

[![Release](https://img.shields.io/github/v/release/Pingy-Dev/pingy-releases?style=for-the-badge&labelColor=0d121c&color=806fff)](https://github.com/Pingy-Dev/pingy-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Pingy-Dev/pingy-releases/total?style=for-the-badge&labelColor=0d121c&color=39dacd)](https://github.com/Pingy-Dev/pingy-releases/releases)
[![Site](https://img.shields.io/badge/сайт-pingy.top-6de6b6?style=for-the-badge&labelColor=0d121c)](https://pingy.top)
[![Telegram](https://img.shields.io/badge/telegram-PingyClient-39dacd?style=for-the-badge&labelColor=0d121c)](https://t.me/PingyClient)

</div>

---

## Скачать

Ссылки **постоянные** — всегда ведут на последнюю версию, их можно сохранять и публиковать.

<div align="center">

| Платформа | Требования | Загрузка |
|:---|:---|:---|
| **Android** | 7.0 и выше, arm64 | [**Скачать APK**](https://github.com/Pingy-Dev/pingy-releases/releases/latest/download/Pingy-Android-arm64.apk) |
| **Windows** | 10 и выше, x64 | [**Скачать установщик**](https://github.com/Pingy-Dev/pingy-releases/releases/latest/download/Pingy-Desktop-x64-setup.exe) |

</div>

Все версии и история изменений — на [странице релизов](https://github.com/Pingy-Dev/pingy-releases/releases).

---

## Что внутри

**Протоколы подключения** — VLESS с XTLS Vision, VMess, Trojan, Shadowsocks, Hysteria2, WireGuard, AmneziaWG 3.1, SOCKS5 и HTTP.

**Транспорт и маскировка** — Reality, TLS 1.3 с uTLS-отпечатками браузеров, XHTTP, gRPC, WebSocket, HTTPUpgrade, mKCP.

**Форматы подписок** — Remnawave, Marzban, обычный список ссылок, base64, Clash YAML и sing-box JSON. Отдельные ключи `vless://`, `vmess://`, `trojan://`, `ss://`, `hy2://`, `wg://` и `awg://` вставляются по одному.

Полный список с пометками о различиях платформ — в [разделе протоколов](https://pingy.top/#protocols), параметры AmneziaWG — в [документации](https://pingy.top/docs#amneziawg).

---

## Проверка подлинности

Скачанный файл стоит сверить перед установкой — это VPN-клиент, и подменённая сборка опаснее обычной.

```
Pingy-Android-arm64.apk        c035548e6bf382179e2b8e53a7afd0069ee7f6a4ecf3c449f0f5968571273428
Pingy-Desktop-x64-setup.exe    c2411e0ca15c992cae60810c5cdf3c91e96117b36b28b8f91f6adc2d59d38646
```

Windows:

```powershell
Get-FileHash .\Pingy-Desktop-x64-setup.exe -Algorithm SHA256
```

Linux и macOS:

```bash
sha256sum Pingy-Android-arm64.apk
```

Контрольные суммы каждой версии публикуются в описании соответствующего релиза.

---

## Ссылки

- Сайт — [pingy.top](https://pingy.top)
- Документация для провайдеров — [pingy.top/docs](https://pingy.top/docs)
- Частые вопросы — [pingy.top/faq](https://pingy.top/faq)
- Канал проекта — [@PingyClient](https://t.me/PingyClient)

---

<div align="center">
<sub>Этот репозиторий содержит только готовые сборки. Исходный код здесь не публикуется.</sub>
</div>
