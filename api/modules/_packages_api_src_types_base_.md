[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["packages/api/src/types/base"](_packages_api_src_types_base_.md)

# Module: "packages/api/src/types/base"

## Index

### Interfaces

* [DecorateMethodOptions](../interfaces/_packages_api_src_types_base_.decoratemethodoptions.md)
* [PaginationOptions](../interfaces/_packages_api_src_types_base_.paginationoptions.md)
* [PromiseResult](../interfaces/_packages_api_src_types_base_.promiseresult.md)
* [RxResult](../interfaces/_packages_api_src_types_base_.rxresult.md)

### Type aliases

* [ApiTypes](_packages_api_src_types_base_.md#apitypes)
* [Cons](_packages_api_src_types_base_.md#cons)
* [DecorateFn](_packages_api_src_types_base_.md#decoratefn)
* [DecorateMethod](_packages_api_src_types_base_.md#decoratemethod)
* [MethodResult](_packages_api_src_types_base_.md#methodresult)
* [ObsInnerType](_packages_api_src_types_base_.md#obsinnertype)
* [PromiseOrObs](_packages_api_src_types_base_.md#promiseorobs)
* [Push](_packages_api_src_types_base_.md#push)
* [UnsubscribePromise](_packages_api_src_types_base_.md#unsubscribepromise)
* [VoidFn](_packages_api_src_types_base_.md#voidfn)

## Type aliases

###  ApiTypes

Ƭ **ApiTypes**: *"promise" | "rxjs"*

*Defined in [packages/api/src/types/base.ts:28](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/base.ts#L28)*

___

###  Cons

Ƭ **Cons**: *function extends function ? R : never*

*Defined in [packages/api/src/types/base.ts:10](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/base.ts#L10)*

___

###  DecorateFn

Ƭ **DecorateFn**: *function*

*Defined in [packages/api/src/types/base.ts:74](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/base.ts#L74)*

#### Type declaration:

▸ (...`args`: any[]): *Observable‹T›*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

___

###  DecorateMethod

Ƭ **DecorateMethod**: *function*

*Defined in [packages/api/src/types/base.ts:82](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/base.ts#L82)*

#### Type declaration:

▸ ‹**Method**›(`method`: Method, `options?`: [DecorateMethodOptions](../interfaces/_packages_api_src_types_base_.decoratemethodoptions.md)): *any*

**Type parameters:**

▪ **Method**: *function*

**Parameters:**

Name | Type |
------ | ------ |
`method` | Method |
`options?` | [DecorateMethodOptions](../interfaces/_packages_api_src_types_base_.decoratemethodoptions.md) |

___

###  MethodResult

Ƭ **MethodResult**: *ApiType extends "rxjs" ? RxResult‹F› : PromiseResult‹F›*

*Defined in [packages/api/src/types/base.ts:63](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/base.ts#L63)*

___

###  ObsInnerType

Ƭ **ObsInnerType**: *O extends Observable‹infer U› ? U : never*

*Defined in [packages/api/src/types/base.ts:31](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/base.ts#L31)*

___

###  PromiseOrObs

Ƭ **PromiseOrObs**: *ApiType extends "rxjs" ? Observable‹T› : Promise‹T›*

*Defined in [packages/api/src/types/base.ts:38](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/base.ts#L38)*

___

###  Push

Ƭ **Push**: *[Push](_packages_api_src_types_base_.md#push)‹T, V›*

*Defined in [packages/api/src/types/base.ts:18](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/base.ts#L18)*

___

###  UnsubscribePromise

Ƭ **UnsubscribePromise**: *Promise‹[VoidFn](_packages_api_src_types_base_.md#voidfn)›*

*Defined in [packages/api/src/types/base.ts:35](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/base.ts#L35)*

___

###  VoidFn

Ƭ **VoidFn**: *function*

*Defined in [packages/api/src/types/base.ts:33](https://github.com/polkadot-js/api/blob/82e71fd51/packages/api/src/types/base.ts#L33)*

#### Type declaration:

▸ (): *void*
