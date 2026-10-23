# Política de privacidade do Washi

Última atualização: 23/10/2026 · vale para o Washi beta (Windows).

## Resumo

- O Washi **não tem conta, não tem cadastro e não envia nada para servidores do Washi**.
- Os seus projetos (`.atelier`), imagens e configurações ficam **no seu computador**.
- Só sai alguma coisa da sua máquina quando **você usa a IA** ou **liga o seu Pinterest**. Nesses casos, o pedido vai para o serviço que você escolheu, como explicado abaixo.

## O que fica só no seu computador

- Projetos, camadas, imagens e a galeria.
- A sua chave do OpenRouter, guardada cifrada pelo próprio Windows.
- O acesso ao seu Pinterest, se você ligar, também guardado cifrado pelo Windows.
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
| Você ligou o Pinterest e pede referências das suas pastas | [Pinterest](https://policy.pinterest.com/pt-br/privacy-policy), com o acesso que você autorizou | o pedido da lista das suas pastas, subpastas e pins, e o download das imagens dos pins escolhidos |

Cada um desses serviços tem a própria política de privacidade. O Washi não vende, não aluga e não usa os seus dados para propaganda.

## Pinterest

- O Pinterest só é ligado se você pedir, pelo login oficial do Pinterest. O login acontece no site do Pinterest, e o Washi **nunca vê a sua senha**.
- O Washi pede **só leitura**: as suas pastas, os seus pins e o nome da sua conta (as permissões `boards:read`, `pins:read` e `user_accounts:read`). Ele **não publica, não edita e não apaga nada** no Pinterest.
- Com isso, o Washi mostra as suas pastas e traz os pins que você ou a IA escolherem como **referência**, na mesa do Builder ou no chat. As imagens ficam no seu computador.
- Nada disso vai para servidores do Washi. Se você mandar um pedido à IA com uma referência do Pinterest anexada, a imagem segue junto para o serviço de IA que você escolheu, como qualquer anexo.
- Para desligar: no Washi, em **Janela › Pinterest (suas pastas)… › Desligar**, o acesso é apagado do computador. Você também pode tirar o acesso do Washi nas configurações da sua conta do Pinterest, na lista de apps com acesso.

## O que o Washi não faz

- Não coleta telemetria, estatísticas de uso nem relatórios de erro automáticos.
- Não lê arquivos fora dos que você abre ou salva.
- Não pede senha, documento ou cartão. **Ninguém do Washi pede a sua chave por mensagem.**

## Como apagar tudo

1. Se ligou o Pinterest, desligue em **Janela › Pinterest (suas pastas)… › Desligar**.
2. Desinstale o Washi pelo Windows (Configurações → Aplicativos).
3. Apague a pasta `%APPDATA%\atelier`, onde ficam as configurações, a galeria e os modelos baixados.
4. Os seus projetos `.atelier` ficam onde você salvou. Apague-os se quiser.

Para cancelar a chave do OpenRouter, apague-a no painel do OpenRouter. Para tirar o acesso do Washi ao Pinterest, faça isso nas configurações da sua conta do Pinterest.

## Crianças

O Washi não é feito para menores de 13 anos e não coleta dados de ninguém de forma intencional.

## Mudanças e contato

Se esta política mudar, a nova versão sai nesta página, com a data no topo.
Dúvidas: abra uma [Issue](https://github.com/mathiassjesus1-spec/washi-beta/issues). Falhas de segurança: veja a [política de segurança](SECURITY.md).
