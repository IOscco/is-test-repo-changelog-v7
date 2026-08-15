# is-test-repo-changelog-v7

## Descripcion y proposito

Repositorio de prueba funcional **publico** con **80 archivos** (subset de mf-apex) para validar changelog multi-archivo, dedup de sync, fallback 406, olas LLM y resiliencia 429 en Confluence DEMO.

Apunta a la pagina Confluence **Documentacion de Sistemas DEMO** (ID `732659714`).

## Repositorio

https://github.com/IOscco/is-test-repo-changelog-v7

## Estructura

```
is-test-repo-changelog-v7/
├── README.md
├── docs/                 # Sync a Confluence
├── src/                  # Codigo representativo (sin data/_raw ni poc JSON masivos)
├── .github/workflows/
└── vite.config.ts
```

## Jira

Prueba funcional: **JIRA-AI-1009**.

- **PR #1:** carga inicial 80 archivos (validacion changelog post-fix AI-970 PR #15).
