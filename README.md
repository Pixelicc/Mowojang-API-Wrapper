# Mowojang-API NPM Wrapper

> [!IMPORTANT]
> This is not an official Wrapper for the [Mowojang-API](https://mowojang.matdoes.dev/)!

## ✨ Quick Start

```TS
import Mowojang from "mowojang"

const UUID = await Mowojang.getUUID("Pixelic")
// or
const username = await Mowojang.getUsername("14727fae-fbdc-4aff-848c-d2713eb9939e")
```

## 🔧 Functions / Supported Endpoints

- `getUUID()`: Converts Username to UUID
- `getUsername()`: Converts UUID to Username
- `getPlayer()`: Retrieve full Player Data by UUID or Username
- `getPlayers()`: Retrieve full Player Data of multiple Players by UUID or Username
- `getPlayerSession()`: Retrieve Player Session Data by UUID or Username

## 🗂️ Validators

- `validateUUID()`: Returns whether the provided String is an valid UUID (Accepts both undashed and dashed UUIDv4 Strings)
- `validateUsername()`: Returns whether the provided String is an valid Username
- `validatePlayer()` Combines the above

## ⚙️ Development

- `pnpm install`: Installs all the required dependencies
- `pnpm build`: Runs the TypeScript compiler
- `pnpm publish`: Publish the Package to NPM or others
