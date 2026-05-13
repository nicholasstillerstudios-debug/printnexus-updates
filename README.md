# PrintNexus — Servidor de Atualizações

Repositório oficial de releases e atualizações automáticas do **PrintNexus v2.0 Premium** — sistema de gestão para gráficas e comunicação visual.

## 📥 Download

Baixe a versão mais recente em [Releases](../../releases).

## 🔄 Auto-update

O PrintNexus consulta este repositório automaticamente para verificar novas versões.

URL do feed de updates (cole nas Configurações do app):

```
https://raw.githubusercontent.com/nicholasstillerstudios-debug/printnexus-updates/main/version.json
```

## 📋 Como funciona

1. App abre → após 5s, lê o `version.json` deste repo
2. Se a versão remota for maior que a instalada → mostra banner de atualização
3. Usuário clica → app baixa o `.exe` da release e roda o instalador

## 🚀 Para publicar nova versão

1. Buildar nova versão do app (`PrintNexus_Setup_X.Y.Z.exe`)
2. Criar release `vX.Y.Z` no GitHub anexando o `.exe`
3. Editar `version.json` com a nova versão e URL
4. Commit + push → todos os clientes recebem a atualização automaticamente
