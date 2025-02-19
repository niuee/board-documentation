[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / Observable

# Class: Observable\<T\>

Defined in: [util/observable.ts:7](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/util/observable.ts#L7)

## Type Parameters

• **T** *extends* `any`[]

## Constructors

### new Observable()

> **new Observable**\<`T`\>(): [`Observable`](Observable.md)\<`T`\>

#### Returns

[`Observable`](Observable.md)\<`T`\>

## Methods

### notify()

> **notify**(...`data`): `void`

Defined in: [util/observable.ts:36](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/util/observable.ts#L36)

#### Parameters

##### data

...`T`

#### Returns

`void`

***

### subscribe()

> **subscribe**(`observer`, `options`?): () => `void`

Defined in: [util/observable.ts:10](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/util/observable.ts#L10)

#### Parameters

##### observer

[`Observer`](../type-aliases/Observer.md)\<`T`\>

##### options?

[`SubscriptionOptions`](../interfaces/SubscriptionOptions.md)

#### Returns

`Function`

##### Returns

`void`
