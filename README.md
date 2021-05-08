# SMCAuditors Smart Contract Audits

We thoroughly check smart contracts to identify security vulnerabilities both manually and using automatically using MythX. We also provide verification that the smart contract is free from logical and access control issues and complies with the Solidity Code Style guide. Typical attack vectors that our security audit investigates includes:

- Replay attacks are valid data transmissions that an attacker records and then maliciously repeats for fraudulent purposes.
- Reentrancy attacks where external calls to untrusted contracts are exploited to introduce unexpected changes to information flows and affect control flows.
- Overflow and underflow conditions that cause the propagation of unexpected data values.
- Reordering attacks are where transactional data is changed by a third-party during the execution of a transaction. 
- Short address attacks are where a contract received less data than expected.
