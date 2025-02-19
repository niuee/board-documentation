[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / InputObserver

# Class: InputObserver

Defined in: [input-observer/input-observer.ts:50](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/input-observer/input-observer.ts#L50)

## Translation Block

This is the observer class that listens to input events and notifies the control center.

## Constructors

### new InputObserver()

> **new InputObserver**(`controlCenter`): [`InputObserver`](InputObserver.md)

Defined in: [input-observer/input-observer.ts:58](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/input-observer/input-observer.ts#L58)

#### Parameters

##### controlCenter

[`InputControlCenter`](../interfaces/InputControlCenter.md)

#### Returns

[`InputObserver`](InputObserver.md)

## Accessors

### controlCenter

#### Get Signature

> **get** **controlCenter**(): [`InputControlCenter`](../interfaces/InputControlCenter.md)

Defined in: [input-observer/input-observer.ts:105](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/input-observer/input-observer.ts#L105)

##### Returns

[`InputControlCenter`](../interfaces/InputControlCenter.md)

#### Set Signature

> **set** **controlCenter**(`value`): `void`

Defined in: [input-observer/input-observer.ts:109](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/input-observer/input-observer.ts#L109)

##### Parameters

###### value

[`InputControlCenter`](../interfaces/InputControlCenter.md)

##### Returns

`void`

## Methods

### notifyOnPan()

> **notifyOnPan**(`diff`): `void`

Defined in: [input-observer/input-observer.ts:62](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/input-observer/input-observer.ts#L62)

#### Parameters

##### diff

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### notifyOnRotation()

> **notifyOnRotation**(`camera`, `deltaRotation`): `void`

Defined in: [input-observer/input-observer.ts:76](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/input-observer/input-observer.ts#L76)

#### Parameters

##### camera

[`DefaultBoardCamera`](DefaultBoardCamera.md)

##### deltaRotation

`number`

#### Returns

`void`

***

### notifyOnZoom()

> **notifyOnZoom**(`deltaZoomAmount`, `anchorPoint`): `void`

Defined in: [input-observer/input-observer.ts:69](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/input-observer/input-observer.ts#L69)

#### Parameters

##### deltaZoomAmount

`number`

##### anchorPoint

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### onInput()

> **onInput**\<`K`\>(`eventName`, `callback`): [`UnsubscribeToUserRawInput`](../type-aliases/UnsubscribeToUserRawInput.md)

Defined in: [input-observer/input-observer.ts:83](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/input-observer/input-observer.ts#L83)

#### Type Parameters

• **K** *extends* keyof [`RawUserInputEventMap`](../type-aliases/RawUserInputEventMap.md)

#### Parameters

##### eventName

`K`

##### callback

(`event`) => `void`

#### Returns

[`UnsubscribeToUserRawInput`](../type-aliases/UnsubscribeToUserRawInput.md)
