# ReportBond demo (Arc Testnet)

This repository exists to try out [ReportBond](https://reportbond-nine.vercel.app):
refundable USDC deposits for private security reports, settled on Arc.

Nothing here is real software. It is a safe place to file test vulnerability
reports and see what happens to the deposit.

## How to try it

1. Get test USDC for Arc Testnet from https://faucet.circle.com.
2. File a private report here: **Security → Report a vulnerability**.
3. Open https://reportbond-nine.vercel.app, find the pool for this repository,
   and choose **Report with deposit**.
4. Sign in with the same GitHub account you filed the report from. Your report
   is listed; pay the deposit for it.
5. The maintainer gives a verdict:
   - **Valid**: you get the deposit back, plus a bounty.
   - **Honest mistake**: you get the deposit back.
   - **Slop** (low-effort or fabricated): the deposit goes to the pool.
   - **No answer before the deadline**: the deposit is refunded automatically.

## Good to know

- This runs on **Arc Testnet**. The USDC has no real value.
- Reports filed here are for testing and may be closed at any time.
- Please don't report real vulnerabilities in other projects here.
