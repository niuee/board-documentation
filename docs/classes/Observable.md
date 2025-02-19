[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / Observable

# Class: Observable\<T\>

Defined in: [util/observable.ts:7](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/util/observable.ts#L7)

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

Defined in: [util/observable.ts:36](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/util/observable.ts#L36)

#### Parameters

##### data

...`T`

#### Returns

`void`

***

### subscribe()

> **subscribe**(`observer`, `options`?): () => `void`

Defined in: [util/observable.ts:10](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/util/observable.ts#L10)

#### Parameters

##### observer

[`Observer`](../type-aliases/Observer.md)\<`T`\>

##### options?

[`SubscriptionOptions`](../interfaces/SubscriptionOptions.md)

#### Returns

`Function`

##### Returns

`void`
