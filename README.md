# Payroll Platform Starter

A minimal starter template for building an on-chain payroll platform.

## Structure

```
.
├── contracts/          # Solidity contracts (Foundry)
├── frontend/          # Next.js frontend (React + Wagmi)
└── README.md
```

## Quick Start

### Contracts

```bash
cd contracts
forge install
forge build
forge test
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

## Tech Stack

- **Contracts**: Solidity, Foundry, OpenZeppelin
- **Frontend**: Next.js, React, TypeScript, Wagmi, Viem, RainbowKit

## Next Steps

1. Review the contract structure in `contracts/src`
2. Review the frontend structure in `frontend/src`
3. Start building your features!

## My Contribution (Hackathon Role)

- Developed major UI sections in React, including invoice input forms, payment views, and confirmation screens.  
- Implemented React logic for reading and displaying contract states (invoice details, payment status, service fees).  
- Integrated the frontend with the blockchain backend using ethers.js, enabling real-time interaction with deployed contracts.  
- Improved user experience by designing clean, intuitive workflows for creating and approving invoices.  
- Worked closely with teammates to align UI with contract functions and overall system design.
