[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["packages/api-derive/src/staking/stakerExposure"](_packages_api_derive_src_staking_stakerexposure_.md)

# Module: "packages/api-derive/src/staking/stakerExposure"

## Index

### Functions

* [_stakerExposure](_packages_api_derive_src_staking_stakerexposure_.md#_stakerexposure)
* [stakerExposure](_packages_api_derive_src_staking_stakerexposure_.md#stakerexposure)

## Functions

###  _stakerExposure

▸ **_stakerExposure**(`api`: ApiInterfaceRx): *function*

*Defined in [packages/api-derive/src/staking/stakerExposure.ts:14](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api-derive/src/staking/stakerExposure.ts#L14)*

**Parameters:**

Name | Type |
------ | ------ |
`api` | ApiInterfaceRx |

**Returns:** *function*

▸ (`accountId`: Uint8Array | string, `eras`: EraIndex[], `withActive`: boolean): *Observable‹DeriveStakerExposure[]›*

**Parameters:**

Name | Type |
------ | ------ |
`accountId` | Uint8Array &#124; string |
`eras` | EraIndex[] |
`withActive` | boolean |

___

###  stakerExposure

▸ **stakerExposure**(`api`: ApiInterfaceRx): *function*

*Defined in [packages/api-derive/src/staking/stakerExposure.ts:40](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api-derive/src/staking/stakerExposure.ts#L40)*

**Parameters:**

Name | Type |
------ | ------ |
`api` | ApiInterfaceRx |

**Returns:** *function*

▸ (`accountId`: Uint8Array | string, `withActive?`: undefined | false | true): *Observable‹DeriveStakerExposure[]›*

**Parameters:**

Name | Type |
------ | ------ |
`accountId` | Uint8Array &#124; string |
`withActive?` | undefined &#124; false &#124; true |
