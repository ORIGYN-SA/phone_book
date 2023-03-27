# Phonebook

### Purpose

This is a placeholder canister to allow Origyn to publish short codes to the perpetualOS until the indexing and directory canisters are complete.

### Usage

Deployment

```
  dfx deploy --network ic phonebook
```

Adding entries

```

dfx canister --network ic call phone_book insert '("brain-matters-demo", vec {principal "ltb2j-maaaa-aaaal-qbuna-cai" })'

```


