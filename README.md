# DonkeSwap Assets Repo
> Repository for the DonkeSwap token assets.

This repository contains the assets for the DonkeSwap tokens list. The assets include the list itself, as well as the token logos.

## Contributing

1. Fork it (<https://github.com/gaiyaa/mytest/fork>)
2. Create your feature branch (`git checkout -b new-token/[token_symbol]`)
3. Add your token to the `sei-evm-tokens-mainnet.json` file
4. Add your token logo to the `logos` directory following the convention `[token_address]/logo.png`. Please ensure that the `[token_address]` folder name matches exactly (including case) with the `address` value in the `sei-evm-tokens-mainnet.json` file.
5. Stage your changes (`git add .`)
6. Commit your changes (`git commit -m 'Add token'`)
7. Push to the branch (`git push origin new-token/[token_symbol]`)
8. Create a new Pull Request

Keep in mind that `sei-evm-tokens-mainnet.json` is the only file, and `logos` the only directory that should be modified. Please do not modify or add any other file or directory.
