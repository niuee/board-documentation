[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / SelectionInputObserver

# Class: SelectionInputObserver

Defined in: [selection-box/selection-input-observer.ts:5](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/selection-box/selection-input-observer.ts#L5)

## Constructors

### new SelectionInputObserver()

> **new SelectionInputObserver**(`camera`, `selectionBox`): [`SelectionInputObserver`](SelectionInputObserver.md)

Defined in: [selection-box/selection-input-observer.ts:14](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/selection-box/selection-input-observer.ts#L14)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### selectionBox

[`SelectionBox`](SelectionBox.md)

#### Returns

[`SelectionInputObserver`](SelectionInputObserver.md)

## Accessors

### selectionBox

#### Get Signature

> **get** **selectionBox**(): [`SelectionBox`](SelectionBox.md)

Defined in: [selection-box/selection-input-observer.ts:10](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/selection-box/selection-input-observer.ts#L10)

##### Returns

[`SelectionBox`](SelectionBox.md)

## Methods

### notifySelectionEndPoint()

> **notifySelectionEndPoint**(`point`): `void`

Defined in: [selection-box/selection-input-observer.ts:24](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/selection-box/selection-input-observer.ts#L24)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### notifySelectionStartPoint()

> **notifySelectionStartPoint**(`point`): `void`

Defined in: [selection-box/selection-input-observer.ts:19](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/selection-box/selection-input-observer.ts#L19)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### toggleSelectionBox()

> **toggleSelectionBox**(`visible`): `void`

Defined in: [selection-box/selection-input-observer.ts:29](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/selection-box/selection-input-observer.ts#L29)

#### Parameters

##### visible

`boolean`

#### Returns

`void`
