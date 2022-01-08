Permita que seus usuários adicionem seu Token BEP20 e Rede Inteligente de Cadeia Binance ao MetaMask.

Suporta MetaMask EIP 747, que define uma maneira de os sites sugerirem um ativo para a carteira de seus usuários rastrear, decidi construir uma ferramenta para fazer isso da maneira mais simples.

apenas altere as opções em `addtometamask.js`, isso é tudo

```
params: {
    'type': 'ERC20',
    'options': {
        'address': '0xe6ce27025f13f5213bbc560dc275e292965a392f',
        'symbol': 'LOOM',
        'decimals': '18',
        'image': 'https://bscscan.com/token/images/loomtoken_32.png',
    },
}
```
