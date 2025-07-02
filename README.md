# UMA.rocks answers chosen by multisig

1. For every voting round, the [uma-bot](https://github.com/lancelot-c/uma-bot) repository creates a pull request in the [uma-answers](https://github.com/lancelot-c/uma-answers) repository.
2. The UMA.rocks multisig owners have 24h to agree on answers for the current voting round, make according changes to the pull request, approve it, and merge it.
3. The uma-bot repo then [fetches](https://github.com/lancelot-c/uma-bot/blob/c9054c6f5b4df1116093a3ecd104dbfe77a66aa8/smart-contract-calls/common.ts#L706) these answers and commit them for all wallets of the pool.

## Who are the UMA.rocks multisig owners?

To be announced
