
To install dependencies
yarn install

To start web server
yarn start


####BUILD METAPLEX CLI
cd metaplex/js/packages/cli/
yarn install
yarn build
yarn run package:linux   // or yarn run package:linuxb
// or npx pkg . -d --targets node14-linux-x64 --output bin/linux/metaplex

sudo cp bin/linux/metaplex /usr/local/bin   // include metaplex cli program to env-path

metaplex upload ./assets --env devnet -k keypair.json_path





quantium@ubuntu /home/quantium-rock/solana-mint/keypair.json
===========================================================================
pubkey: ANrUXjHkLTHFnBzgKJTy5atKnGMBWG9RqvCvZJrK1VPF
===========================================================================
Save this seed phrase and your BIP39 passphrase to recover your new keypair:
anchor actress before milk meat fiscal change card story immense come delay
===========================================================================

local: solana-mint/keypair.json
===========================================================================
pubkey: ARcK7PrdebzPcbHN3yb4NrU9gsHtx8HCMZC7tRq5x1U2
===========================================================================
Save this seed phrase and your BIP39 passphrase to recover your new keypair:
curious episode wall ankle cute pride pretty rent giggle arena stuff spirit
===========================================================================

create generative art metaplex (build):
ts-node build/candy-machine-cli.js create_generative_art -n 891

create candy-machine:
npx ts-node ~/solana-mint/metaplex/js/packages/cli/src/candy-machine-cli.ts 

npx ts-node src/candy-machine-cli.ts upload metaplex/assets -e devnet -k keypair.json -n 10 // OR
upload metaplex/assets -e devnet -k keypair.json -n 4

update candy-machine:
ts-node ~/metaplex-foundation/metaplex/js/packages/cli/src/candy-machine-cli.ts \
    update_candy_machine \
    --env devnet \
    --keypair ~/.config/solana/devnet.json \
    --price 1 \
    --date "26 Sep 2021 00:12:00 GMT"

Commands
- Use "-h" to see the available options for the command
npx ts-node metaplex/js/packages/cli/src/candy-machine-cli.ts -h
npx ts-node metaplex/js/packages/cli/src/candy-machine-cli.ts upload
npx ts-node metaplex/js/packages/cli/src/candy-machine-cli. create_candy_machine
npx ts-node metaplex/js/packages/cli/src/candy-machine-cli.ts update_candy_machine


npx ts-node metaplex/js/packages/cli/src/candy-machine-cli.ts upload metaplex/assets -e devnet -k keypair.json -n 4

#Cherry
=======

1. upload_arweave: 
npx ts-node metaplex/js/packages/cli/src/candy-machine-cli.ts upload metaplex/js/packages/cli/assets -e devnet -k keypair.json -n 891
    Beginning the upload for 891 (png+json) pairs
    started at: 1637008543173
    wallet public key: ARcK7PrdebzPcbHN3yb4NrU9gsHtx8HCMZC7tRq5x1U2
    Done. Successful = true.
    ended at: 2021-11-15T20:35:43.998Z. time taken: 00:00:00
    (devnet)

2. verify_arweave: 
npx ts-node metaplex/js/packages/cli/src/candy-machine-cli.ts verify metaplex/js/packages/cli/assets -e devnet -k keypair.json -n 891

3. build_candy_machine:
npx ts-node metaplex/js/packages/cli/build/candy-machine-cli.js create_candy_machine -e devnet -k keypair.json -s ARcK7PrdebzPcbHN3yb4NrU9gsHtx8HCMZC7tRq5x1U2 -p 1
    wallet public key: ARcK7PrdebzPcbHN3yb4NrU9gsHtx8HCMZC7tRq5x1U2
    create_candy_machine finished. candy machine pubkey: HPEGkKmPPTzLjQzRXwtnpnuhgsmUPY3tT83Mp3pQPxa3

    config: 4f8YC8v5fxJyf9wY8BvVsLz23C4azqqMViu4mpXupWXn

create_candy_machine:
=====================



npx ts-node metaplex/js/packages/cli/src/candy-machine-cli.ts upload metaplex/assets -e devnet -k keypair.json -n 4

npx ts-node metaplex/js/packages/cli/src/candy-machine-cli.ts verify metaplex/assets -e devnet -k keypair.json

npx ts-node metaplex/js/packages/cli/build/candy-machine-cli.js create_candy_machine -e devnet -k keypair.json -s ARcK7PrdebzPcbHN3yb4NrU9gsHtx8HCMZC7tRq5x1U2 -p 1

npx ts-node metaplex/js/packages/cli/build/candy-machine-cli.js update_candy_machine -k keypair.json --date '16 Oct 2021 20:43 UTC'


wallet public key: ARcK7PrdebzPcbHN3yb4NrU9gsHtx8HCMZC7tRq5x1U2
create_candy_machine finished. candy machine pubkey: FATsaWnQQmsFN7Sbm7u7btxVSKUxKNvbkqX6MAYGAe9V

date=1634416980


.env

REACT_APP_CANDY_MACHINE_CONFIG=CHNSx7fEadKeYyUpw4UNM3HPQpXVR42BrMokMUCMVWrU
REACT_APP_CANDY_MACHINE_ID=FATsaWnQQmsFN7Sbm7u7btxVSKUxKNvbkqX6MAYGAe9V
REACT_APP_TREASURY_ADDRESS=ARcK7PrdebzPcbHN3yb4NrU9gsHtx8HCMZC7tRq5x1U2
REACT_APP_CANDY_START_DATE=1634416980

REACT_APP_SOLANA_NETWORK=devnet
REACT_APP_SOLANA_RPC_HOST=https://explorer-api.devnet.solana.com




##### LAST COMMANDS

npx ts-node metaplex/js/packages/cli/src/candy-machine-cli.ts upload metaplex/js/packages/cli/assets -e testnet -k keypair.json -n 10

npx ts-node metaplex/js/packages/cli/src/candy-machine-cli.ts verify metaplex/js/packages/cli/assets -e testnet -k keypair.json

npx ts-node metaplex/js/packages/cli/build/candy-machine-cli.js create_candy_machine -e testnet -k keypair.json -s ARcK7PrdebzPcbHN3yb4NrU9gsHtx8HCMZC7tRq5x1U2 -p 0.22




