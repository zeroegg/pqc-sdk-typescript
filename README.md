# QLabs PQC SDK - TypeScript

**Status**: 🚧 Coming Soon (Beta: Q2 2026)

TypeScript/JavaScript SDK for QLabs PQC Signature API.

## Installation

```bash
npm install @qlabs/pqc-sdk  # Coming soon
```

## Quick Start

```typescript
import { PQCClient } from '@qlabs/pqc-sdk';

const client = new PQCClient({ apiKey: 'your_api_key' });
const signature = await client.sign({ message: 'Hello, quantum world!' });
console.log(signature);
```

## Documentation

Full docs: https://docs.qlabsai.com/sdk/typescript

## Beta Access

👉 [Join the waitlist](https://api.qlabsai.com) for early access.

---

© 2025 QLabs. MIT License.
