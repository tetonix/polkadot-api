[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["packages/api/src/types/storage"](../modules/_packages_api_src_types_storage_.md) › [StorageEntryDoubleMap](_packages_api_src_types_storage_.storageentrydoublemap.md)

# Interface: StorageEntryDoubleMap ‹**ApiType, F**›

## Type parameters

▪ **ApiType**: *[ApiTypes](../modules/_packages_api_src_types_base_.md#apitypes)*

▪ **F**: *AnyFunction*

## Hierarchy

* [StorageEntryBase](_packages_api_src_types_storage_.storageentrybase.md)‹ApiType, F›

  ↳ **StorageEntryDoubleMap**

## Index

### Properties

* [at](_packages_api_src_types_storage_.storageentrydoublemap.md#at)
* [creator](_packages_api_src_types_storage_.storageentrydoublemap.md#creator)
* [entries](_packages_api_src_types_storage_.storageentrydoublemap.md#entries)
* [entriesPaged](_packages_api_src_types_storage_.storageentrydoublemap.md#entriespaged)
* [hash](_packages_api_src_types_storage_.storageentrydoublemap.md#hash)
* [key](_packages_api_src_types_storage_.storageentrydoublemap.md#key)
* [keyPrefix](_packages_api_src_types_storage_.storageentrydoublemap.md#keyprefix)
* [keys](_packages_api_src_types_storage_.storageentrydoublemap.md#keys)
* [keysPaged](_packages_api_src_types_storage_.storageentrydoublemap.md#keyspaged)
* [multi](_packages_api_src_types_storage_.storageentrydoublemap.md#multi)
* [range](_packages_api_src_types_storage_.storageentrydoublemap.md#range)
* [size](_packages_api_src_types_storage_.storageentrydoublemap.md#size)

## Properties

###  at

• **at**: *function*

*Inherited from [StorageEntryBase](_packages_api_src_types_storage_.storageentrybase.md).[at](_packages_api_src_types_storage_.storageentrybase.md#at)*

*Defined in [packages/api/src/types/storage.ts:29](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/storage.ts#L29)*

#### Type declaration:

▸ ‹**T**›(`hash`: Hash | Uint8Array | string, ...`args`: Parameters‹F›): *[PromiseOrObs](../modules/_packages_api_src_types_base_.md#promiseorobs)‹ApiType, T›*

**Type parameters:**

▪ **T**: *Codec | any*

**Parameters:**

Name | Type |
------ | ------ |
`hash` | Hash &#124; Uint8Array &#124; string |
`...args` | Parameters‹F› |

___

###  creator

• **creator**: *StorageEntry*

*Inherited from [StorageEntryBase](_packages_api_src_types_storage_.storageentrybase.md).[creator](_packages_api_src_types_storage_.storageentrybase.md#creator)*

*Defined in [packages/api/src/types/storage.ts:30](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/storage.ts#L30)*

___

###  entries

• **entries**: *function*

*Inherited from [StorageEntryBase](_packages_api_src_types_storage_.storageentrybase.md).[entries](_packages_api_src_types_storage_.storageentrybase.md#entries)*

*Defined in [packages/api/src/types/storage.ts:31](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/storage.ts#L31)*

#### Type declaration:

▸ ‹**T**›(`arg?`: Parameters‹F›[0]): *[PromiseOrObs](../modules/_packages_api_src_types_base_.md#promiseorobs)‹ApiType, [StorageKey, T][]›*

**Type parameters:**

▪ **T**: *Codec | any*

**Parameters:**

Name | Type |
------ | ------ |
`arg?` | Parameters‹F›[0] |

___

###  entriesPaged

• **entriesPaged**: *function*

*Inherited from [StorageEntryBase](_packages_api_src_types_storage_.storageentrybase.md).[entriesPaged](_packages_api_src_types_storage_.storageentrybase.md#entriespaged)*

*Defined in [packages/api/src/types/storage.ts:32](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/storage.ts#L32)*

#### Type declaration:

▸ ‹**T**›(`opts`: [PaginationOptions](_packages_api_src_types_base_.paginationoptions.md)‹Parameters‹F›[0]›): *[PromiseOrObs](../modules/_packages_api_src_types_base_.md#promiseorobs)‹ApiType, [StorageKey, T][]›*

**Type parameters:**

▪ **T**: *Codec | any*

**Parameters:**

Name | Type |
------ | ------ |
`opts` | [PaginationOptions](_packages_api_src_types_base_.paginationoptions.md)‹Parameters‹F›[0]› |

___

###  hash

• **hash**: *function*

*Inherited from [StorageEntryBase](_packages_api_src_types_storage_.storageentrybase.md).[hash](_packages_api_src_types_storage_.storageentrybase.md#hash)*

*Defined in [packages/api/src/types/storage.ts:33](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/storage.ts#L33)*

#### Type declaration:

▸ (...`args`: Parameters‹F›): *[PromiseOrObs](../modules/_packages_api_src_types_base_.md#promiseorobs)‹ApiType, Hash›*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | Parameters‹F› |

___

###  key

• **key**: *function*

*Inherited from [StorageEntryBase](_packages_api_src_types_storage_.storageentrybase.md).[key](_packages_api_src_types_storage_.storageentrybase.md#key)*

*Defined in [packages/api/src/types/storage.ts:34](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/storage.ts#L34)*

#### Type declaration:

▸ (...`args`: Parameters‹F›): *string*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | Parameters‹F› |

___

###  keyPrefix

• **keyPrefix**: *function*

*Overrides [StorageEntryBase](_packages_api_src_types_storage_.storageentrybase.md).[keyPrefix](_packages_api_src_types_storage_.storageentrybase.md#keyprefix)*

*Defined in [packages/api/src/types/storage.ts:44](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/storage.ts#L44)*

#### Type declaration:

▸ (`key1?`: Parameters‹F›[0]): *string*

**Parameters:**

Name | Type |
------ | ------ |
`key1?` | Parameters‹F›[0] |

___

###  keys

• **keys**: *function*

*Inherited from [StorageEntryBase](_packages_api_src_types_storage_.storageentrybase.md).[keys](_packages_api_src_types_storage_.storageentrybase.md#keys)*

*Defined in [packages/api/src/types/storage.ts:36](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/storage.ts#L36)*

#### Type declaration:

▸ (`arg?`: any): *[PromiseOrObs](../modules/_packages_api_src_types_base_.md#promiseorobs)‹ApiType, StorageKey[]›*

**Parameters:**

Name | Type |
------ | ------ |
`arg?` | any |

___

###  keysPaged

• **keysPaged**: *function*

*Inherited from [StorageEntryBase](_packages_api_src_types_storage_.storageentrybase.md).[keysPaged](_packages_api_src_types_storage_.storageentrybase.md#keyspaged)*

*Defined in [packages/api/src/types/storage.ts:37](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/storage.ts#L37)*

#### Type declaration:

▸ (`opts`: [PaginationOptions](_packages_api_src_types_base_.paginationoptions.md)‹Parameters‹F›[0]›): *[PromiseOrObs](../modules/_packages_api_src_types_base_.md#promiseorobs)‹ApiType, StorageKey[]›*

**Parameters:**

Name | Type |
------ | ------ |
`opts` | [PaginationOptions](_packages_api_src_types_base_.paginationoptions.md)‹Parameters‹F›[0]› |

___

###  multi

• **multi**: *ApiType extends "rxjs" ? StorageEntryObservableMulti : StorageEntryPromiseMulti*

*Inherited from [StorageEntryBase](_packages_api_src_types_storage_.storageentrybase.md).[multi](_packages_api_src_types_storage_.storageentrybase.md#multi)*

*Defined in [packages/api/src/types/storage.ts:40](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/storage.ts#L40)*

___

###  range

• **range**: *function*

*Inherited from [StorageEntryBase](_packages_api_src_types_storage_.storageentrybase.md).[range](_packages_api_src_types_storage_.storageentrybase.md#range)*

*Defined in [packages/api/src/types/storage.ts:38](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/storage.ts#L38)*

#### Type declaration:

▸ ‹**T**›(`__namedParameters`: [string | Uint8Array‹› | Hash‹›, undefined | string | Uint8Array‹› | Hash‹›], ...`args`: Parameters‹F›): *[PromiseOrObs](../modules/_packages_api_src_types_base_.md#promiseorobs)‹ApiType, [Hash, T][]›*

**Type parameters:**

▪ **T**: *Codec | any*

**Parameters:**

Name | Type |
------ | ------ |
`__namedParameters` | [string &#124; Uint8Array‹› &#124; Hash‹›, undefined &#124; string &#124; Uint8Array‹› &#124; Hash‹›] |
`...args` | Parameters‹F› |

___

###  size

• **size**: *function*

*Inherited from [StorageEntryBase](_packages_api_src_types_storage_.storageentrybase.md).[size](_packages_api_src_types_storage_.storageentrybase.md#size)*

*Defined in [packages/api/src/types/storage.ts:39](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/storage.ts#L39)*

#### Type declaration:

▸ (...`args`: Parameters‹F›): *[PromiseOrObs](../modules/_packages_api_src_types_base_.md#promiseorobs)‹ApiType, u64›*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | Parameters‹F› |
