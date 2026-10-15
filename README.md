# Washi — beta grátis

**Photoshop + Figma num app só, com IA trabalhando direto nas camadas.**
Pincel, máscara, vetor e texto editáveis: a IA monta a peça e você termina do seu jeito.

[![Versão](https://img.shields.io/github/v/release/mathiassjesus1-spec/washi-beta?label=vers%C3%A3o&color=111111)](https://github.com/mathiassjesus1-spec/washi-beta/releases/latest)
![Windows 10/11](https://img.shields.io/badge/Windows-10%20%7C%2011-111111)
![Grátis no beta](https://img.shields.io/badge/beta-gr%C3%A1tis-2ea043)
![Versão imutável](https://img.shields.io/badge/vers%C3%A3o-imut%C3%A1vel-2ea043)
[![VirusTotal](https://img.shields.io/badge/VirusTotal-0%2F58%20antiv%C3%ADrus-2ea043)](https://www.virustotal.com/gui/file/48bd19aef86f024726b85e1f0c2601e05bbc5251fb60a729bba7ce866a03155f)
![Microsoft Defender](https://img.shields.io/badge/Microsoft%20Defender-0%20amea%C3%A7as-2ea043)

**Novo na 0.8.1:** abertura mais rápida, com tela de entrada, e a tela dos planos (no beta, tudo continua grátis).

## ⬇️ Baixar

1. Abra **[a versão mais nova](https://github.com/mathiassjesus1-spec/washi-beta/releases/latest)**.
2. Em **Assets**, baixe o **`Washi-0.8.1-instalador.exe`** (Windows 10/11, 64 bits).
3. Dê dois cliques e siga o instalador.

### O que é cada arquivo da versão

| Arquivo | O que é | Precisa baixar? |
|---|---|---|
| `Washi-0.8.1-instalador.exe` | **O app.** É o instalador do Washi. | ✅ **Sim, só este** |
| `SHA256SUMS.txt` | A "impressão digital" do instalador, para conferir se ele é o original (veja abaixo). | Opcional |
| `Source code (zip)` / `Source code (tar.gz)` | O GitHub coloca sozinho em toda versão. Tem só os textos desta página, **não o app** e não o código dele. | ❌ Não |

### O que é cada arquivo desta página

| Arquivo | O que é |
|---|---|
| `README.md` | Esta página. |
| `LICENCA.txt` | Os termos de uso (os mesmos que aparecem na instalação). |
| `PRIVACIDADE.md` | O que o Washi guarda e o que envia. Resumo: nada vai para servidores do Washi. |
| `SECURITY.md` | Como se proteger e como nos avisar de uma falha em particular. |
| `SHA256SUMS.txt` | A impressão digital da versão atual. |

## 🔒 Por que é seguro

| O que garante | Como você confere |
|---|---|
| **Sem vírus.** O instalador passou em **58 antivírus no VirusTotal (Google): 0 detecções**, e no Microsoft Defender: 0 ameaças (15/10/2026). | Veja o [resultado público no VirusTotal](https://www.virustotal.com/gui/file/48bd19aef86f024726b85e1f0c2601e05bbc5251fb60a729bba7ce866a03155f), ou clique com o botão direito no arquivo baixado → *Verificar com o Microsoft Defender*. |
| **O arquivo é o original.** A impressão digital SHA-256 muda inteira se mudar um único byte. | No PowerShell, na pasta do download: `Get-FileHash .\Washi-0.8.1-instalador.exe -Algorithm SHA256`. O resultado tem que ser igual ao `SHA256SUMS.txt`. O GitHub mostra o mesmo código ao lado do arquivo, em *Assets*. |
| **Ninguém troca o instalador depois de publicado**, nem nós. A versão é **imutável**: o GitHub bloqueia trocar arquivos e mover a etiqueta. | Na página da versão aparece o selo **Immutable**. |
| **Não precisa de senha de administrador.** | No instalador, escolha instalar só para você. |
| **Não coleta seus dados.** Sem conta, sem cadastro e sem telemetria. Os projetos ficam no seu computador. | Veja a [política de privacidade](PRIVACIDADE.md). |
| **A sua chave de IA fica guardada criptografada** pelo próprio Windows e só vai para o OpenRouter. | Ninguém do Washi pede a sua chave por mensagem. |
| **O app roda isolado.** A tela do editor não tem acesso direto ao sistema (sandbox do Electron), e as ferramentas de desenvolvedor vêm desligadas. | — |

Baixe **só por esta página**. Cópias em outros sites não são nossas.

## ⚠️ O Windows avisou "O Windows protegeu o computador"?

**É esperado.** Esse aviso aparece em todo app novo que ainda não tem a assinatura digital da Microsoft. Ele não quer dizer que o arquivo tem vírus. Estamos finalizando a assinatura do Washi pela **Microsoft Store**; quando ela sair, o aviso some.

Para instalar agora:
1. Clique em **Mais informações**.
2. Clique em **Executar assim mesmo**.

## 🗓️ Validade do beta

Este beta é **gratuito** e vale **por tempo limitado**. Antes de terminar, o app avisa com 7 dias de antecedência. Depois disso, ele pede a versão nova, e os seus projetos (`.atelier`) continuam no seu computador.

## 🤖 IA

A IA usa a **sua chave do OpenRouter** (dá para usar os modelos gratuitos) ou, em breve, um plano Washi. Os geradores de imagem e vídeo são os que você escolher no painel.

## 👥 Quem faz o Washi

O Washi é feito por uma equipe: uma pessoa e vários agentes de IA trabalhando juntos.

- **Mathias**: criador, designer e diretor do produto. Decide o que entra, desenha a interface e testa cada versão.
- **Agentes de IA**, coordenados por ele no mesmo projeto:
  - **Claude** (Anthropic): arquitetura, motor de pintura, camadas, máscaras e formato dos arquivos.
  - **Codex** (OpenAI): ferramentas vetoriais, zoom, salvar e abrir.
  - **Astra**: frentes em paralelo com os outros agentes.
  - **Cursor**: painéis da interface (nas primeiras versões).

O que os agentes escrevem passa por testes automáticos e pela revisão do Mathias antes de virar versão.

## 🐞 Achou um erro?

Abra uma **[Issue](https://github.com/mathiassjesus1-spec/washi-beta/issues)** ou comente no vídeo. Cada erro relatado no beta é corrigido.
Falha de segurança: não abra Issue. Use **Security → Report a vulnerability** (aviso privado).

---

© Washi. Todos os direitos reservados. Este repositório contém apenas o instalador e os textos. O código do app não é público.
