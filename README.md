# ENS

ENS module for ens domain management on the Ethereum blockchain.

# Usage

## Init

```ts
// Provider is an instance of 0xcert framework provider.
const ens = new Ens(provider, NetworkKind.ROPSTEN);
```

## Resolve domain into address

```ts
const address = await ens.getAddress('domain.eth');
```

## Get domain from address

```ts
const domain = await ens.getDomain('address');
```

# Live example

Live example is available for ropsten network on codesandbox:
https://codesandbox.io/s/github/0xcert/ens-example?module=%2FREADME.md