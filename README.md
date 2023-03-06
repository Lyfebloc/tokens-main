# Lyfebloc Token Assets

This repository is a comprehensive collection of token assets for pooled tokens on Lyfebloc.

Token logos are stored according to their address under the `assets/<chain-id>/` directory.
Token images are stored in the format `<token-address>/logo_24.png` and `<token-address>/logo_48.png`.

## Add Yours
1. Create a new directory named using your [checksum token address](https://web3js.readthedocs.io/en/v1.7.1/web3-utils.html#tochecksumaddress).
2. Add your 24x24 token image as a file named `logo_24.png` inside the directory.
3. Add your 48x48 token image as a file named `logo_48.png` inside the directory.
4. No image should be larger than 10 KB.
5. Token should be [verified on an explorer like etherscan.io](https://etherscan.io/verifyContract).
6. Create a PR titled `Add [TOKEN_NAME]` to the `main` branch.

## Example directory structures
```
├─ tokens/
└─┬─ assets/
  └─┬─[chain_id]/
    │
    ├─┬─ 0x317472CCb2b741E87bc0F76B4C0c325C80E9D851/
    │ ├── logo_24.png
    │ └── logo_48.png
    │
    ├─┬─ 0x3348263DA42decB32bDcA8e27F7A5FA8534B47eE/
    │ ├── logo_24.png
    │ └── logo_48.png
    │
 ...
```

## Disclaimer
Lyfebloc allows anyone to submit new assets to this repository.
However, this does not mean that Lyfebloc is in direct partnership with any project.

Lyfebloc will reject projects that are deemed as a scam or fraudulent after review.
Lyfebloc reserves the right to change the terms of asset submissions at any time due to changing market conditions, risk of fraud, or any other factors we deem relevant.
