# 🛠️ Tools & Setup

Repositório centralizado para automação de infraestrutura local, scripts utilitários e arquivos de configuração (**dotfiles**). Projetado para realizar o provisionamento rápido de ambientes de desenvolvimento em múltiplos sistemas operacionais.

> "A automação não é sobre ganhar tempo, é sobre garantir que o ambiente seja idêntico e funcional toda vez." — **Guilherme Sene**

---

## 📂 Estrutura do Projeto

O repositório é organizado por ecossistemas para facilitar a portabilidade e manutenção:

* **[macos/](./macos)**: Automação de setup, gerenciamento de pacotes e customização do ambiente Apple.
* **[windows/](./windows)**: Scripts de provisionamento e listas de software para ambientes Windows.
* **[linux/](./linux)**: Configurações de shell e scripts de instalação para distribuições Linux.
* **[vscode/](./vscode)**: Padronização do editor de código e gerenciamento de extensões.

---

## 🚀 Como utilizar no macOS (Manual)

Siga os passos abaixo para configurar seu ambiente macOS clonando o repositório e executando a instalação controlada:

### 1. Clonar o repositório
Abra o Terminal, escolha um local de sua preferência e clone o projeto:
```bash
git clone [https://github.com/Senedev/Tools.git](https://github.com/Senedev/Tools.git)
cd Tools/macos

2. Executar o script e aguardar a instalação
brew bundle --file=Brewfile

3. Realizar a limpeza dos arquivos temporários
brew autoremove && brew cleanup --prune=all