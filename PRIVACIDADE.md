# Política de privacidade do Washi

Última atualização: 15/10/2026 · vale para o Washi beta (Windows).

## Resumo

- O Washi **não tem conta, não tem cadastro e não envia nada para servidores do Washi**.
- Os seus projetos (`.atelier`), imagens e configurações ficam **no seu computador**.
- Só sai alguma coisa da sua máquina quando **você usa a IA**. Nesse caso, o pedido vai para o serviço de IA que você escolheu, como explicado abaixo.

## O que fica só no seu computador

- Projetos, camadas, imagens e a galeria.
- A sua chave do OpenRouter, guardada cifrada pelo próprio Windows.
- A voz: o ditado é transcrito **no computador**, com um modelo local. O áudio não sai da máquina.
- O recorte de fundo também roda no computador, com um modelo local.

## O que sai do computador, e só quando você usa

| Quando | Para onde | O que vai |
|---|---|---|
| Você faz um pedido à IA | [OpenRouter](https://openrouter.ai/privacy), com a sua chave, e de lá para o modelo que você escolheu | o texto do pedido, as imagens ou camadas que você anexou e o necessário da prancheta para a IA trabalhar |
| A IA gera uma imagem ou um vídeo | o gerador escolhido no painel, via OpenRouter | a descrição da imagem e as referências anexadas |
| A IA pesquisa uma referência na web | DuckDuckGo ou Bing | só os termos da pesquisa |
| No primeiro uso da voz | Hugging Face | download do modelo de voz; nada seu é enviado |
| Ao abrir o app | Google Fonts | download das fontes da interface |

Cada um desses serviços tem a própria política de privacidade. O Washi não vende, não aluga e não usa os seus dados para propaganda.

## O que o Washi não faz

- Não coleta telemetria, estatísticas de uso nem relatórios de erro automáticos.
- Não lê arquivos fora dos que você abre ou salva.
- Não pede senha, documento ou cartão. **Ninguém do Washi pede a sua chave por mensagem.**

## Como apagar tudo

1. Desinstale o Washi pelo Windows (Configurações → Aplicativos).
2. Apague a pasta `%APPDATA%\atelier`, onde ficam as configurações, a galeria e os modelos baixados.
3. Os seus projetos `.atelier` ficam onde você salvou. Apague-os se quiser.

Para cancelar a chave do OpenRouter, apague-a no painel do OpenRouter.

## Crianças

O Washi não é feito para menores de 13 anos e não coleta dados de ninguém de forma intencional.

## Mudanças e contato

Se esta política mudar, a nova versão sai nesta página, com a data no topo.
Dúvidas: abra uma [Issue](https://github.com/mathiassjesus1-spec/washi-beta/issues). Falhas de segurança: veja a [política de segurança](SECURITY.md).
