# Changelog

## 0.12.0

### Minor Changes

- **feat**: reduces the number of commands to run for the user in the contracts folder #168 (2a27b64)
- **chore**: code refactoring to make the app easier to test #167

## 0.11.0

### Minor Changes

- **fix**: mitigate a supply-chain attack on the `@ledgerhq/connect-kit` package. (846aa54)

## 0.10.0

### Minor Changes

- **feat**: added `yarn build` check in CI #155 #156 (20ea771)
- **fix**: moved `pages` to hold only pages, and components/hooks/styles under `src`. Also removed ts paths since they tend to cause issues. #153
- **feat**: setup Perfume.js and Web Vitals metrics #152
- **feat**: started a new homepage with a CodeBlock component #151
- **docs**: added [Stackblitz](https://stackblitz.com/github/coinbase/build-onchain-apps/tree/main/apps/build-onchain-apps) for a quick live code demo access #148
- **feat**: added ABI Types with `abitype` #146

## 0.9.1

### Patch Changes

- **fix**: added missing import and dependecies for Tailwind to work (#143) (b4b09c1)
- **fix**: now jest coverage works, and it's pretty nice (#142)
- **feat**: Initial setup for mobile menu (#137)

## 0.9.0

### Patch Changes

- **docs**: easier instructions and setup (#138) (5028c14)
- **feat**: replaced Typescript "ES5" target with "ES2020" (#136)
- **feat**: added ERC1155 contracts (#133)
- **feat**: setting up the initial Jest configuration and tests (#128) (#134)
- **feat**: added Lint and Tests into the Github Actions for apps/build-onchain-apps (#135)

## 0.8.0

### Minor Changes

- **feat**: upgraded from v1 to Yarn v4 (#123) (4c62641)
- **feat**: added Foundry support (#119)
- **feat**: added Basic Mint page example (#117)
- **feat**: init support Web Vitals with the Perfume.js library (#113)

## 0.7.3

### Patch Changes

- **feat** : create Navbar component using @radix-ui/react-navigation-menu (d0f433b)

## 0.7.2

### Patch Changes

- **feat** : converted App into a Progressive Web App (2fb70ad)

## 0.7.1

### Patch Changes

- **docs**: onchain app is now lowercase (241fdb8)

## 0.7.0

### Minor Changes

- **fea**: moved repo to @coinbase/build-onchain-apps (8cccd55)

## 0.6.0

### Minor Changes

**feat**: supported more Wallets with RainbowKit (#85)(9c3d3ed)

## 0.5.0

### Minor Changes

- **feat**: renaming templates into apps (#80) (f776f3f)

## 0.4.1

### Patch Changes

- **feat**: reversed the memos order (1203109).

## 0.4.0

### Minor Changes

- **feat**: replaced Infura with Alchemy (7ecd7ee).
- **feat**: did some nice styling on `AccountConnectButton`.
- **feat**: started a shared onchain types file.
- **fix**: got Base Goerli working properly again.
- **chore**: update viem and clean up yarn.lock.
- **chore**: moved a few of the common functions inside the utils folder.

## 0.3.0

### Minor Changes

- **feat**: replaced RainbowKit with Coinbase Wallet SDK 💙 (734c828)
- **feat**: started shaping `AccountConnectButton` onchain component

## 0.2.2

### Patch Changes

- **feat**: added some nice Linting for import/order (a77dc73)
- **feat**: added onchain/ folder to keep nice and neat all Onchain TS specific code
- **feat**: added NEXT_PUBLIC_INFURA_ID in .env.example
- **chore**: moved the code a bit around, so all Onchain code is mostly in one folder

## 0.2.1

### Patch Changes

- **fix**: polish README and fix a few console errors (1eac3f8)

## 0.2.0

### Minor Changes

- **feat**: moved templates created inside apps/ #59

## 0.1.3

### Patch Changes

- **fix**: bin path pointing to wrong folder.

## 0.1.2

### Patch Changes

- **fix**: CLI broken by missing dist files

## 0.1.1

### Patch Changes

- **chore**: release CLI

## 0.1.0

### Minor Changes

- **feat**: new build-onchain-apps CLI for onchain app creation

## 0.0.4

### Patch Changes

- **chore:** added some extra context in the README.md

## 0.0.3

### Patch Changes

- **feat:** adding buy me a coffee feature for demo reading from smart contract #7
- **chore:** added lint checks as script and in CI #11 (#18)
- **chore:** setup Github Actions format workflow #12
- **chore:** added prettier and did a nice first run ✨ #2 (#14)
- **docs** added Documentation Request template #4 (#6)
- **chore** setup initial scaffolding
