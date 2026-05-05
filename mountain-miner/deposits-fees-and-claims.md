# Deposits, Fees & Claims

## Deposit Fee

Mountain Miner uses a 5% deposit fee.

Example:

```text
Deposit: 100 USDC
Deposit fee: 5 USDC
Net deposit: 95 USDC
```

The net deposit is what counts toward the user's earning base and 3X max payout.

## Max Payout

Mountain Miner uses a 3X max payout based on net deposit.

Example:

```text
Net deposit: 95 USDC
Max payout: 95 × 3 = 285 USDC
```

## Claim Fee

Claims have a 5% fee.

Example:

```text
Claim amount: 10 USDC
Claim fee: 0.50 USDC
User receives: 9.50 USDC
```

## Compound Example

Although the UI does not include a compound button, a user can manually claim and redeposit.

Example:

```text
Original deposit: 100 USDC
Deposit fee: 5 USDC
Original net deposit: 95 USDC
Original max payout: 285 USDC
```

If the user claims 10 USDC:

```text
Claim amount: 10 USDC
Claim fee: 0.50 USDC
User receives: 9.50 USDC
```

If the user redeposits the 9.50 USDC:

```text
Redeposit amount: 9.50 USDC
Deposit fee: 0.475 USDC
Additional net deposit: 9.025 USDC
```

The user's new net deposit would be approximately:

```text
95 + 9.025 = 104.025 USDC
```

The new max payout would be approximately:

```text
104.025 × 3 = 312.075 USDC
```

## Project Guidance

Manual compounding can increase a user's max payout and can also increase project fee capture. However, the project strongly recommends that users focus on ROI first before considering compound-style strategies.

Compounding increases exposure and does not remove the risk that the contract balance may decline over time.
