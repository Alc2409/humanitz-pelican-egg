# HumanitZ Pelican Egg

Egg do servidor dedicado Linux do HumanitZ para Pelican.

## Importação

Use o arquivo [`egg-humanitz.json`](./egg-humanitz.json) na importação de eggs do Pelican.

## Estrutura esperada

O egg utiliza a estrutura atual do servidor Linux:

```text
HumanitZServer/Binaries/Linux/HumanitZServer-Linux-Shipping
HumanitZServer/GameServerSettings.ini
```

## Portas

- `SERVER_PORT`: porta do jogo, normalmente `7777`
- `QUERY_PORT`: porta Steam Query, normalmente `27015`
- `RCON_PORT`: porta TCP do RCON, normalmente `8888`, quando o RCON estiver habilitado

Libere as portas necessárias em UDP e TCP conforme a configuração da hospedagem.

## Configuração

O egg inclui as opções de gameplay documentadas na referência oficial do HumanitZ, incluindo host, experiência, respawn, raridade de loot, IA, clima, animais, construção, manutenção, voz, RCON e busca do servidor. Algumas chaves legadas foram mantidas para compatibilidade com versões anteriores do servidor.

A referência oficial recomenda manter `SEARCH_ID` como `HumanitZ_Dedicated` para aparecer na lista pública padrão. O marcador de inicialização do Pelican é `Session created!`.

## Fonte

- [HumanitZ Wiki — Server Configuration Files](https://humanitz.wiki.gg/wiki/Server_Configuration_Files)
