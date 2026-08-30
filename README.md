# 🖨️ SGCMI — Central de Downloads & Releases do Print Agent

Repositório oficial de distribuição e atualizações remotas do **SGCMI Print Agent** (Agente Desktop de Impressão Térmica de Etiquetas e Pulseiras para o Ministério Infantil).

---

## 📥 Downloads Oficiais

| Arquivo | Descrição | Link Direto |
| :--- | :--- | :---: |
| **Instalador Completo** | Assistente de instalação para Windows 10 e 11 (64-bit) | [⬇️ Baixar Setup (.exe)](https://github.com/matheus159753/sgcmi_downloads/releases/latest/download/SGCMI_Print_Agent_Setup.exe) |
| **Executável Avulso** | Binário nativo autocontido para substituição e auto-update | [⬇️ Baixar Executável (.exe)](https://github.com/matheus159753/sgcmi_downloads/releases/latest/download/SGCMI_Print_Agent.exe) |
| **Última Release** | Notas de versão, changelog e hashes de integridade SHA-256 | [🏷️ Ver Última Release](https://github.com/matheus159753/sgcmi_downloads/releases/latest) |

---

## 🖥️ Requisitos do Sistema

- **Sistema Operacional:** Windows 10 ou Windows 11 (64-bit / x64)
- **Runtime:** Microsoft Edge WebView2 (instalado automaticamente pelo assistente se necessário)
- **Conectividade:** Acesso à internet para sincronização com o backend SGCMI (`https://sgcmi.org`)
- **Impressoras Suportadas:** Impressoras térmicas USB / Rede (Brother QL-800, Zebra, Elgin, Argox, etc.)

---

## 🔄 Atualizações Automáticas

O **SGCMI Print Agent** possui rotina de auto-update transparente em segundo plano:
1. Consulta periodicamente a API pública de releases deste repositório (`/releases/latest`).
2. Compara a versão local instalada com a versão mais recente publicada.
3. Realiza o download seguro e o swap atômico do binário sem necessidade de intervenção do operador.

---

© **SGCMI** — Sistema de Gestão e Controle do Ministério Infantil
