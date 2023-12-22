learn-substrate
===============

```
git clone https://github.com/substrate-developer-hub/substrate-node-template
cd substrate-node-template && cargo build --release
./target/release/node-template --dev
```

```
node --version
# npm install --global yarn
yarn --version
git clone https://github.com/substrate-developer-hub/substrate-front-end-template
cd substrate-front-end-template && yarn install
yarn start
# http://localhost:8080/substrate-front-end-template
```

---

https://docs.substrate.io/tutorials/

https://docs.substrate.io/tutorials/smart-contracts/

https://docs.substrate.io/tutorials/smart-contracts/prepare-your-first-contract/

https://github.com/paritytech/substrate-contracts-node

https://github.com/paritytech/substrate-contracts-node/blob/main/runtime/src/lib.rs

---

https://crates.parity.io/pallet_contracts_rpc_runtime_api/trait.ContractsApi.html

https://docs.substrate.io/reference/how-to-guides/pallet-design/incorporate-randomness/

https://docs.rs/pallet-contracts/latest/pallet_contracts/pallet/trait.Config.html

https://docs.rs/pallet-nicks/latest/pallet_nicks/pallet/trait.Config.html

https://github.com/paritytech/cargo-contract

```
cargo install --force --locked cargo-contract 
cargo contract new flipper
cargo contract build
cargo test
```

(https://contracts-ui.substrate.io/ : upload ./target/ink/flipper.contract)

