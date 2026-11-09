# TOTVS Storex Ecosystem Hub

Portal unificado de documentação e engenharia da suíte **TOTVS Storex** para o varejo físico e omnichannel.

Hospedado no GitHub Pages: **https://edneyfs.github.io/storex-site/**

---

## 🏛️ Estrutura de Módulos

| Diretório | Produto | Status | Descrição |
| :--- | :--- | :---: | :--- |
| **`/SCK/`** | **Linx Self-Checkout** | 🟢 **Disponível (v3.41)** | Frente de caixa de autoatendimento (totem touch, RFID, TEF SiTef, Pix, SMTP, NPS Formbricks). |
| **`/LWS/`** | **Storex Cloud** | ⏳ Em Breve | Retaguarda em nuvem, gestão de catálogo e motor promocional central. |
| **`/CXR/`** | **Storex Mobile** | ⏳ Em Breve | Frente de caixa móvel Android para atendimento volante e quebra de filas no salão. |
| **`/CONFIG/`** | **Servidor de Configuração** | ⏳ Em Breve | Gestão centralizada de parâmetros, feature flags e perfis de hardware. |
| **`/Integration/`** | **Storex Integration** | ⏳ Em Breve | Barramento de conectores corporativos com ERPs TOTVS e plataformas omnichannel. |
| **`/Sync/`** | **Storex Integration Sync** | ⏳ Em Breve | Serviço de sincronização e mensageria de alta resiliência offline-first. |

---

## 🚀 Como Atualizar e Publicar no GitHub

Para atualizar este repositório no GitHub:

```bash
# 1. No repositório self-checkout, execute o build unificado:
yarn storex:build

# 2. Navegue até a pasta storex-site e envie as alterações:
cd storex-site
git add .
git commit -m "feat: atualiza Storex Hub e documentacao viva do SCK"
git push
```

A GitHub Action configurada em `.github/workflows/deploy.yml` fará o deploy instantâneo para o GitHub Pages!
