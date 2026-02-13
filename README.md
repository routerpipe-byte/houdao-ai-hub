# 🚀 Houdao AI Hub

**One Key · 500+ AI Models · Pay only ~30%**

OpenAI-compatible API gateway for unified access to 500+ models.

🌐 **Languages:** **EN** | [中文](README.zh-CN.md) | [Español](README.es-ES.md)

---

## Why Houdao?

- **One API Key** to access 500+ AI models (OpenAI / Claude / Gemini / DeepSeek / Qwen / GLM and more)
- **Pay only ~30%** compared to official pricing (varies by model)
- **OpenAI API compatible**: drop-in replacement by changing `base_url`
- Built for developers: stable, scalable, production-ready

---

## Quick Start

### cURL
```bash
curl https://newapi.houdao.com/v1/chat/completions \
  -H "Authorization: Bearer YOUR_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "gpt-4o",
    "messages": [{"role":"user","content":"Hello from Houdao!"}]
  }'
