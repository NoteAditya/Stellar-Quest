# 🚀 Stellar Quest by Stellar India 🌟

Welcome, adventurer! 🎒 Get ready to explore the amazing world of Stellar through our interactive quests. Each quest will teach you something new about the Stellar network while you earn cool badges along the way. Let’s get started! 💪

## 📜 Table of Contents

1. [Quest 1: Create Account](#-quest-1-create-account)
2. [Quest 2: Payment](#-quest-2-payment)
3. [Quest 3: Change Trust (Trustline)](#-quest-3-change-trust-trustline)
4. [Quest 4: Manage Offer](#-quest-4-manage-offer)
5. [Quest 5: Path Payment](#-quest-5-path-payment)
6. [Quest 6: Account Merge](#%EF%B8%8F-quest-6-account-merge)
7. [Quest 7: Manage Data](#-quest-7-manage-data)
8. [Quest 8: Set Options - Home Domain](#-quest-8-set-options---home-domain)
9. [Quest 9: Set Options - Weights, Thresholds, and Signers](#%EF%B8%8F-quest-9-set-options---weights-thresholds-and-signers)
10. [Quest 10: Set Flags](#-quest-10-set-flags)
11. [Quest 11: Bump Sequence](#-quest-11-bump-sequence)
12. [Quest 12: Sponsorships](#-quest-12-sponsorships)
13. [Quest 13: Claimable Balances](#-quest-13-claimable-balances)
14. [Quest 14: Clawbacks](#-quest-13-claimable-balances)
15. [Quest 15: Liquidity Pools](#-quest-15-liquidity-pools)

## 🛠️ Prerequisites

- Basic understanding of blockchain technology
- Access to the Stellar Laboratory
- A funded Stellar account on the testnet
- A browser with internet access

## 🏃 Getting Started

1. Visit the [Stellar Laboratory](https://www.stellar.org/laboratory/)
2. Fund your Quest Keypair using the "Fund" button
3. Follow the instructions for each quest below

---

## 🌐 Quest 1: Create Account

**Objective:** Create a new account using the `createAccount` operation.

1. Navigate to the Build Transaction tab
2. Select "Create Account" as the operation type
3. Input the destination account public key
4. Set the starting balance
5. Sign and submit the transaction

---

## 💰 Quest 2: Payment

**Objective:** Perform a payment operation.

1. Navigate to the Build Transaction tab
2. Select "Payment" as the operation type
3. Input the destination account public key
4. Select the asset (XLM)
5. Set the amount
6. Sign and submit the transaction

---

## 🔗 Quest 3: Change Trust (Trustline)

**Objective:** Establish a trustline for a custom asset using the `changeTrust` operation.

1. Navigate to the Build Transaction tab
2. Select "Change Trust" as the operation type
3. Input the asset code (alphanumeric 4 or 12)
4. Input the issuer account public key
5. Set the trust limit (leave blank for maximum)
6. Sign and submit the transaction

---

## 🛒 Quest 4: Manage Offer

**Objective:** Create a buy or sell offer using the `manageBuyOffer`, `manageSellOffer`, or `createPassiveSellOffer` operation.

1. Navigate to the Build Transaction tab
2. Select "Manage Buy Offer", "Manage Sell Offer", or "Create Passive Sell Offer"
3. Configure the selling and buying assets
4. Set the amount and price
5. Sign and submit the transaction

---

## 🔄 Quest 5: Path Payment

**Objective:** Perform a path payment.

1. Navigate to the Build Transaction tab
2. Select "Path Payment Strict Send" or "Path Payment Strict Receive" as the operation type
3. Input the destination account public key
4. Select the sending and destination assets
5. Set the send amount or destination amount
6. Sign and submit the transaction

---

## 🗑️ Quest 6: Account Merge

**Objective:** Delete an account by merging it with another.

1. Navigate to the Build Transaction tab
2. Select "Account Merge" as the operation type
3. Input the destination account public key
4. Sign and submit the transaction

---

## 📊 Quest 7: Manage Data

**Objective:** Add a data entry to an account.

1. Navigate to the Build Transaction tab
2. Select "Manage Data" as the operation type
3. Input the entry name and value
4. Sign and submit the transaction

---

## 🏠 Quest 8: Set Options - Home Domain

**Objective:** Set the Home Domain for an account.

1. Create and host a `stellar.toml` file
2. Navigate to the Build Transaction tab
3. Select "Set Options" as the operation type
4. Input the Home Domain
5. Sign and submit the transaction

---

## 🛡️ Quest 9: Set Options - Weights, Thresholds, and Signers

**Objective:** Configure account thresholds and signers.

1. Navigate to the Build Transaction tab
2. Select "Set Options" as the operation type
3. Set the Master Weight and Thresholds
4. Add additional signers
5. Sign and submit the transaction

---

## 🚩 Quest 10: Set Flags

**Objective:** Issue an asset with the Authorization Required flag set and then revoke authorization using the Authorization Revocable flag.

1. Navigate to the Build Transaction tab
2. Set the Authorization Required and Authorization Revocable flags on the issuing account
3. Create a trustline from the Quest Account to the issuing account
4. Authorize the Quest Account to hold the asset
5. Send the asset to the Quest Account
6. Revoke the Quest Account’s authorization to hold the asset
7. Sign and submit the transaction

---

## 🔀 Quest 11: Bump Sequence

**Objective:** Increase the sequence number of the Quest Account.

1. Navigate to the Build Transaction tab
2. Use the Bump Sequence operation to increase the sequence number
3. Sign and submit the transaction
4. Create a new transaction starting from the bumped-to sequence number
5. Sign and submit the new transaction

---

## 🤝 Quest 12: Sponsorships

**Objective:** Set up a sponsored account with zero balance.

1. Create a new account on the testnet (sponsoring account)
2. Use the Begin Sponsoring Future Reserves operation
3. Create the Quest Account with the sponsoring account paying the base reserve
4. Use the End Sponsoring Future Reserves operation
5. Sign and submit the transaction

---

## 🎁 Quest 13: Claimable Balances

**Objective:** Create and claim a claimable balance.

1. Create a new account on the testnet (Account 2)
2. Use the Create Claimable Balance operation with a predicate
3. Claim the claimable balance with Account 2
4. Sign and submit the transactions

---

## 🦅 Quest 14: Clawbacks

**Objective:** Issue an asset and then claw it back.

1. Set the Clawback Enabled flag on the issuing account
2. Issue the asset to another account
3. Use the Clawback operation to claw back the asset
4. Sign and submit the transactions

---

## 🌊 Quest 15: Liquidity Pools

**Objective:** Create a liquidity pool, use it for a path payment, and withdraw from it.

1. Create a new account on the testnet (Account 2)
2. Establish trustlines for the assets and liquidity pool shares
3. Create and deposit into the liquidity pool
4. Use the liquidity pool for a path payment
5. Withdraw from the liquidity pool
6. Sign and submit the transactions

---

## 📚 Resources

- [Stellar Laboratory](https://www.stellar.org/laboratory/)
- [Stellar Expert](https://stellar.expert/)
- [Stellar Documentation](https://developers.stellar.org/docs/)
- [Stellar Quest Discord](https://discord.gg/stellar)
- [Stellar India Twitter(X)](https://x.com/stellar_ind)
- [Stellar India Telegram](https://t.me/stellarindia)

## 🛠️ Troubleshooting

- If a transaction fails, check the error message for details
- Ensure all required fields are filled correctly
- Verify that your account has sufficient balance
- Consult the Stellar community for assistance

---

## 🎉 Good luck on your Stellar Quest journey! 🚀

Have fun, learn a lot, and earn those badges! 🎒🌟
