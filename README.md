# dkeeper

Welcome to your new dkeeper project and to the internet computer development community.

If you want to start working on your project right away, you might want to try the following commands:

```bash
cd dkeeper/
dfx help
dfx config --help
```

## Running the project locally

If you want to test your project locally, you can use the following commands:

```bash
# Starts the replica, running in the background
dfx start --background

# Deploys your canisters to the replica and generates your candid interface
dfx deploy
```

Once the job completes, your application will be available at `http://127.0.0.1:8000/?canisterId={asset_canister_id}`.

## About
Its basically a simple todo app where i use react on front end side.

And for backend purpose i use internet computer blockchain, and motoko stable variables so that your list does not get lost even after refresing and re-deploying.

