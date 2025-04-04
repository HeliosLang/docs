---
sidebar_label: T StakingValidatorHash
---
# `StakingValidatorHash`

[Opaque](https://en.wikipedia.org/wiki/Opaque_data_type) [`ByteArray`](./bytearray.md) that represents the hash of a staking script.

## Associated functions

### `new`

```helios
StakingValidatorHash::new(bytes: ByteArray) -> StakingValidatorHash
```

### `from_data`

```helios
StakingValidatorHash::from_data(data: Data) -> StakingValidatorHash
```

### `from_script_hash`

Casts the generic [`ScriptHash`](./scripthash.md) type into `StakingValidatorHash`.

```helios
StakingValidatorHash::from_script_hash(hash: ScriptHash) -> StakingValidatorHash
```

## Getters

### `bytes`

```helios
staking_validator_hash.bytes -> ByteArray
```

## Operators

### `==`

```helios
StakingValidatorHash == StakingValidatorHash -> Bool
```

### `!=`

```helios
StakingValidatorHash != StakingValidatorHash -> Bool
```

### `>=`

```helios
StakingValidatorHash >= StakingValidatorHash -> Bool
```

### `>`

```helios
StakingValidatorHash > StakingValidatorHash -> Bool
```

### `<=`

```helios
StakingValidatorHash <= StakingValidatorHash -> Bool
```

### `<`

```helios
StakingValidatorHash < StakingValidatorHash -> Bool
```

## Methods

### `serialize`

```helios
staking_validator_hash.serialize() -> ByteArray
```

### `show`

Hexadecimal representation of the `StakingValidatorHash`.

```helios
staking_validator_hash.show() -> String
```