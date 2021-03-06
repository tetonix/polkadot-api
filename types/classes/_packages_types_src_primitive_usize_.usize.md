[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["packages/types/src/primitive/USize"](../modules/_packages_types_src_primitive_usize_.md) › [USize](_packages_types_src_primitive_usize_.usize.md)

# Class: USize

**`name`** USize

**`description`** 
A System default unsigned number, typically used in RPC to report non-consensus
data. It is a wrapper for [U32](_packages_types_src_primitive_u32_.u32.md) as a WASM default (as generated by Rust bindings).
It is not to be used, since it created consensus mismatches.

## Hierarchy

  ↳ [U32](_packages_types_src_primitive_u32_.u32.md)

  ↳ **USize**

## Implements

* [Codec](../interfaces/_packages_types_src_types_codec_.codec.md)

## Index

### Interfaces

* [MPrime](../interfaces/_packages_types_src_primitive_usize_.usize.mprime.md)
* [ReductionContext](../interfaces/_packages_types_src_primitive_usize_.usize.reductioncontext.md)

### Type aliases

* [Endianness](_packages_types_src_primitive_usize_.usize.md#static-endianness)
* [IPrimeName](_packages_types_src_primitive_usize_.usize.md#static-iprimename)

### Constructors

* [constructor](_packages_types_src_primitive_usize_.usize.md#constructor)

### Methods

* [with](_packages_types_src_primitive_usize_.usize.md#static-with)

## Type aliases

### `Static` Endianness

Ƭ **Endianness**: *"le" | "be"*

Defined in node_modules/@types/bn.js/index.d.ts:11

___

### `Static` IPrimeName

Ƭ **IPrimeName**: *"k256" | "p224" | "p192" | "p25519"*

Defined in node_modules/@types/bn.js/index.d.ts:12

## Constructors

###  constructor

\+ **new USize**(`registry`: [Registry](../interfaces/_packages_types_src_types_registry_.registry.md), `value?`: unknown): *[USize](_packages_types_src_primitive_usize_.usize.md)*

*Overrides [UInt](_packages_types_src_codec_uint_.uint.md).[constructor](_packages_types_src_codec_uint_.uint.md#constructor)*

*Defined in [packages/types/src/primitive/USize.ts:16](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/primitive/USize.ts#L16)*

**Parameters:**

Name | Type |
------ | ------ |
`registry` | [Registry](../interfaces/_packages_types_src_types_registry_.registry.md) |
`value?` | unknown |

**Returns:** *[USize](_packages_types_src_primitive_usize_.usize.md)*

## Methods

### `Static` with

▸ **with**(`bitLength`: [UIntBitLength](../modules/_packages_types_src_codec_abstractint_.md#uintbitlength), `typeName?`: undefined | string): *[Constructor](../interfaces/_packages_types_src_types_codec_.constructor.md)‹[UInt](_packages_types_src_codec_uint_.uint.md)›*

*Inherited from [UInt](_packages_types_src_codec_uint_.uint.md).[with](_packages_types_src_codec_uint_.uint.md#static-with)*

*Defined in [packages/types/src/codec/UInt.ts:24](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/UInt.ts#L24)*

**Parameters:**

Name | Type |
------ | ------ |
`bitLength` | [UIntBitLength](../modules/_packages_types_src_codec_abstractint_.md#uintbitlength) |
`typeName?` | undefined &#124; string |

**Returns:** *[Constructor](../interfaces/_packages_types_src_types_codec_.constructor.md)‹[UInt](_packages_types_src_codec_uint_.uint.md)›*
