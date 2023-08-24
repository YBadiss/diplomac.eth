# diplomac.eth

```mermaid
graph LR
    client(Client) -- uses --> wallet(Wallet)
    client -- auth, read, sign actions --> app(App)
    app -- auth, write signed actions --> service(Service)
    service -- verify, write signed actions --> chain(Chain)
    app -- read --> chain(Chain)
```

- [x] Basic App and Service with SIWE https://github.com/spruceid/siwe-quickstart/tree/main/03_complete_app
- [ ] Sign a simple EIP-712 message, stored by the Service
- [ ] Define interface of game data
- [ ] Implement mock of game data retrieval
- [ ] Create smart contract
- [ ] ...
