[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["packages/types/src/codec/Raw"](../modules/_packages_types_src_codec_raw_.md) › [Raw](_packages_types_src_codec_raw_.raw.md)

# Class: Raw

**`name`** Raw

**`description`** 
A basic wrapper around Uint8Array, with no frills and no fuss. It does differ
from other implementations where it will consume the full Uint8Array as passed to it.
As such it is meant to be subclassed where the wrapper takes care of the
actual lengths instead of used directly.

## Hierarchy

* [Uint8Array](_packages_types_src_codec_raw_.raw.md#static-uint8array)

  ↳ **Raw**

  ↳ [U8aFixed](_packages_types_src_codec_u8afixed_.u8afixed.md)

  ↳ [ImmortalEra](_packages_types_src_extrinsic_extrinsicera_.immortalera.md)

  ↳ [Bytes](_packages_types_src_primitive_bytes_.bytes.md)

  ↳ [BitVec](_packages_types_src_primitive_bitvec_.bitvec.md)

## Implements

* [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md)

## Indexable

* \[ **index**: *number*\]: number

**`name`** Raw

**`description`** 
A basic wrapper around Uint8Array, with no frills and no fuss. It does differ
from other implementations where it will consume the full Uint8Array as passed to it.
As such it is meant to be subclassed where the wrapper takes care of the
actual lengths instead of used directly.

## Index

### Constructors

* [constructor](_packages_types_src_codec_raw_.raw.md#constructor)

### Properties

* [registry](_packages_types_src_codec_raw_.raw.md#readonly-registry)
* [Uint8Array](_packages_types_src_codec_raw_.raw.md#static-uint8array)

### Accessors

* [encodedLength](_packages_types_src_codec_raw_.raw.md#encodedlength)
* [hash](_packages_types_src_codec_raw_.raw.md#hash)
* [isAscii](_packages_types_src_codec_raw_.raw.md#isascii)
* [isEmpty](_packages_types_src_codec_raw_.raw.md#isempty)
* [isUtf8](_packages_types_src_codec_raw_.raw.md#isutf8)
* [length](_packages_types_src_codec_raw_.raw.md#length)

### Methods

* [bitLength](_packages_types_src_codec_raw_.raw.md#bitlength)
* [eq](_packages_types_src_codec_raw_.raw.md#eq)
* [subarray](_packages_types_src_codec_raw_.raw.md#subarray)
* [toHex](_packages_types_src_codec_raw_.raw.md#tohex)
* [toHuman](_packages_types_src_codec_raw_.raw.md#tohuman)
* [toJSON](_packages_types_src_codec_raw_.raw.md#tojson)
* [toRawType](_packages_types_src_codec_raw_.raw.md#torawtype)
* [toString](_packages_types_src_codec_raw_.raw.md#tostring)
* [toU8a](_packages_types_src_codec_raw_.raw.md#tou8a)
* [toUtf8](_packages_types_src_codec_raw_.raw.md#toutf8)

## Constructors

###  constructor

\+ **new Raw**(`registry`: [Registry](../interfaces/_packages_types_src_types_registry_.registry.md), `value?`: [AnyU8a](../modules/_packages_types_src_types_helpers_.md#anyu8a)): *[Raw](_packages_types_src_codec_raw_.raw.md)*

*Defined in [packages/types/src/codec/Raw.ts:30](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L30)*

**Parameters:**

Name | Type |
------ | ------ |
`registry` | [Registry](../interfaces/_packages_types_src_types_registry_.registry.md) |
`value?` | [AnyU8a](../modules/_packages_types_src_types_helpers_.md#anyu8a) |

**Returns:** *[Raw](_packages_types_src_codec_raw_.raw.md)*

## Properties

### `Readonly` registry

• **registry**: *[Registry](../interfaces/_packages_types_src_types_registry_.registry.md)*

*Implementation of [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md).[registry](../interfaces/_packages_types_src_types_interfaces_.iu8a.md#readonly-registry)*

*Defined in [packages/types/src/codec/Raw.ts:30](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L30)*

___

### `Static` Uint8Array

▪ **Uint8Array**: *Uint8ArrayConstructor*

Defined in node_modules/typescript/lib/lib.es5.d.ts:2263

## Accessors

###  encodedLength

• **get encodedLength**(): *number*

*Defined in [packages/types/src/codec/Raw.ts:41](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L41)*

**`description`** The length of the value when encoded as a Uint8Array

**Returns:** *number*

___

###  hash

• **get hash**(): *H256*

*Defined in [packages/types/src/codec/Raw.ts:48](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L48)*

**`description`** returns a hash of the contents

**Returns:** *H256*

___

###  isAscii

• **get isAscii**(): *boolean*

*Defined in [packages/types/src/codec/Raw.ts:55](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L55)*

**`description`** Returns true if the wrapped value contains only ASCII printable characters

**Returns:** *boolean*

___

###  isEmpty

• **get isEmpty**(): *boolean*

*Defined in [packages/types/src/codec/Raw.ts:62](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L62)*

**`description`** Returns true if the type wraps an empty/default all-0 value

**Returns:** *boolean*

___

###  isUtf8

• **get isUtf8**(): *boolean*

*Defined in [packages/types/src/codec/Raw.ts:69](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L69)*

**`description`** Returns true if the wrapped value contains only utf8 characters

**Returns:** *boolean*

___

###  length

• **get length**(): *number*

*Overrides [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md).[length](../interfaces/_packages_types_src_types_interfaces_.iu8a.md#readonly-length)*

*Defined in [packages/types/src/codec/Raw.ts:76](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L76)*

**`description`** The length of the value

**Returns:** *number*

## Methods

###  bitLength

▸ **bitLength**(): *number*

*Implementation of [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md)*

*Defined in [packages/types/src/codec/Raw.ts:84](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L84)*

**`description`** Returns the number of bits in the value

**Returns:** *number*

___

###  eq

▸ **eq**(`other?`: unknown): *boolean*

*Implementation of [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md)*

*Defined in [packages/types/src/codec/Raw.ts:91](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L91)*

**`description`** Compares the value of the input to see if there is a match

**Parameters:**

Name | Type |
------ | ------ |
`other?` | unknown |

**Returns:** *boolean*

___

###  subarray

▸ **subarray**(`begin`: number, `end?`: undefined | number): *[Uint8Array](_packages_types_src_codec_raw_.raw.md#static-uint8array)*

*Overrides [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md).[subarray](../interfaces/_packages_types_src_types_interfaces_.iu8a.md#subarray)*

*Defined in [packages/types/src/codec/Raw.ts:105](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L105)*

**`description`** Create a new subarray from the actual buffer. This is needed for compat reasons since a new Uint8Array gets returned here

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`begin` | number | The position to start at |
`end?` | undefined &#124; number | The position to end at  |

**Returns:** *[Uint8Array](_packages_types_src_codec_raw_.raw.md#static-uint8array)*

___

###  toHex

▸ **toHex**(): *string*

*Defined in [packages/types/src/codec/Raw.ts:112](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L112)*

**`description`** Returns a hex string representation of the value

**Returns:** *string*

___

###  toHuman

▸ **toHuman**(): *[AnyJson](../modules/_packages_types_src_types_helpers_.md#anyjson)*

*Defined in [packages/types/src/codec/Raw.ts:119](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L119)*

**`description`** Converts the Object to to a human-friendly JSON, with additional fields, expansion and formatting of information

**Returns:** *[AnyJson](../modules/_packages_types_src_types_helpers_.md#anyjson)*

___

###  toJSON

▸ **toJSON**(): *string*

*Implementation of [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md)*

*Defined in [packages/types/src/codec/Raw.ts:128](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L128)*

**`description`** Converts the Object to JSON, typically used for RPC transfers

**Returns:** *string*

___

###  toRawType

▸ **toRawType**(): *string*

*Implementation of [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md)*

*Defined in [packages/types/src/codec/Raw.ts:135](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L135)*

**`description`** Returns the base runtime type name for this instance

**Returns:** *string*

___

###  toString

▸ **toString**(): *string*

*Implementation of [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md)*

*Overrides [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md).[toString](../interfaces/_packages_types_src_types_interfaces_.iu8a.md#tostring)*

*Defined in [packages/types/src/codec/Raw.ts:142](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L142)*

**`description`** Returns the string representation of the value

**Returns:** *string*

___

###  toU8a

▸ **toU8a**(`isBare?`: undefined | false | true): *[Uint8Array](_packages_types_src_codec_raw_.raw.md#static-uint8array)*

*Defined in [packages/types/src/codec/Raw.ts:151](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L151)*

**`description`** Encodes the value as a Uint8Array as per the SCALE specifications

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`isBare?` | undefined &#124; false &#124; true | true when the value has none of the type-specific prefixes (internal)  |

**Returns:** *[Uint8Array](_packages_types_src_codec_raw_.raw.md#static-uint8array)*

___

###  toUtf8

▸ **toUtf8**(): *string*

*Defined in [packages/types/src/codec/Raw.ts:158](https://github.com/polkadot-js/api/blob/82e71fd51/packages/types/src/codec/Raw.ts#L158)*

**`description`** Returns the wrapped data as a UTF-8 string

**Returns:** *string*
