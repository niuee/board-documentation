[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / RawUserInputObservable

# Class: RawUserInputObservable

Defined in: [input-observer/input-observer.ts:118](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-observer/input-observer.ts#L118)

## Constructors

### new RawUserInputObservable()

> **new RawUserInputObservable**(`inputControlCenter`): [`RawUserInputObservable`](RawUserInputObservable.md)

Defined in: [input-observer/input-observer.ts:126](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-observer/input-observer.ts#L126)

#### Parameters

##### inputControlCenter

[`InputControlCenter`](../interfaces/InputControlCenter.md)

#### Returns

[`RawUserInputObservable`](RawUserInputObservable.md)

## Accessors

### controlCenter

#### Get Signature

> **get** **controlCenter**(): [`InputControlCenter`](../interfaces/InputControlCenter.md)

Defined in: [input-observer/input-observer.ts:167](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-observer/input-observer.ts#L167)

##### Returns

[`InputControlCenter`](../interfaces/InputControlCenter.md)

## Methods

### notifyPan()

> **notifyPan**(`diff`): `void`

Defined in: [input-observer/input-observer.ts:134](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-observer/input-observer.ts#L134)

#### Parameters

##### diff

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### notifyRotate()

> **notifyRotate**(`deltaRotation`): `void`

Defined in: [input-observer/input-observer.ts:146](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-observer/input-observer.ts#L146)

#### Parameters

##### deltaRotation

`number`

#### Returns

`void`

***

### notifyZoom()

> **notifyZoom**(`deltaZoomAmount`, `anchorPoint`): `void`

Defined in: [input-observer/input-observer.ts:140](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-observer/input-observer.ts#L140)

#### Parameters

##### deltaZoomAmount

`number`

##### anchorPoint

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### on()

> **on**\<`K`\>(`eventName`, `callback`): [`UnsubscribeToUserRawInput`](../type-aliases/UnsubscribeToUserRawInput.md)

Defined in: [input-observer/input-observer.ts:152](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-observer/input-observer.ts#L152)

#### Type Parameters

• **K** *extends* keyof [`RawUserInputEventMap`](../type-aliases/RawUserInputEventMap.md)

#### Parameters

##### eventName

`K`

##### callback

(`event`) => `void`

#### Returns

[`UnsubscribeToUserRawInput`](../type-aliases/UnsubscribeToUserRawInput.md)
