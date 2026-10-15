# Segurança

## Baixe só daqui
O único lugar oficial do Washi beta é **https://github.com/mathiassjesus1-spec/washi-beta/releases**.
Sites que "espelham" o instalador não são nossos: não baixe deles.

## Confira o arquivo
Cada versão publica o `SHA256SUMS.txt`. No PowerShell:

```powershell
Get-FileHash .\Washi-0.8.1-instalador.exe -Algorithm SHA256
```

O resultado tem que ser **igual** ao do `SHA256SUMS.txt` da mesma versão. Se for diferente, não instale.

## Suas chaves
- O Washi **nunca** pede sua senha do OpenRouter, do Google ou de qualquer conta. Ele pede só a **chave de API** do OpenRouter, que fica guardada criptografada no seu computador.
- Ninguém do Washi vai pedir sua chave por mensagem, e-mail ou comentário.

## Achou uma falha de segurança?
Não abra uma Issue pública. Use **Security → Report a vulnerability** neste repositório (aviso privado). Respondemos o quanto antes.
