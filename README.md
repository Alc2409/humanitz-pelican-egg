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

Libere as portas necessárias em UDP e TCP conforme a configuração da hospedagem.

## Observações

O Pelican considera o servidor iniciado quando encontra `Session created!` no console.
