[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / SelectionBox

# Class: SelectionBox

Defined in: [drawing-engine/selection-box.ts:4](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/drawing-engine/selection-box.ts#L4)

## Implements

- [`DrawTask`](../interfaces/DrawTask.md)

## Constructors

### new SelectionBox()

> **new SelectionBox**(`context`): [`SelectionBox`](SelectionBox.md)

Defined in: [drawing-engine/selection-box.ts:11](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/drawing-engine/selection-box.ts#L11)

#### Parameters

##### context

[`CanvasRenderingContext2D`](https://developer.mozilla.org/docs/Web/API/CanvasRenderingContext2D)

#### Returns

[`SelectionBox`](SelectionBox.md)

## Accessors

### endPoint

#### Get Signature

> **get** **endPoint**(): [`Point`](../type-aliases/Point.md)

Defined in: [drawing-engine/selection-box.ts:31](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/drawing-engine/selection-box.ts#L31)

##### Returns

[`Point`](../type-aliases/Point.md)

#### Set Signature

> **set** **endPoint**(`point`): `void`

Defined in: [drawing-engine/selection-box.ts:27](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/drawing-engine/selection-box.ts#L27)

##### Parameters

###### point

[`Point`](../type-aliases/Point.md)

##### Returns

`void`

***

### startPoint

#### Get Signature

> **get** **startPoint**(): [`Point`](../type-aliases/Point.md)

Defined in: [drawing-engine/selection-box.ts:23](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/drawing-engine/selection-box.ts#L23)

##### Returns

[`Point`](../type-aliases/Point.md)

#### Set Signature

> **set** **startPoint**(`point`): `void`

Defined in: [drawing-engine/selection-box.ts:18](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/drawing-engine/selection-box.ts#L18)

##### Parameters

###### point

[`Point`](../type-aliases/Point.md)

##### Returns

`void`

## Methods

### clearSelection()

> **clearSelection**(): `void`

Defined in: [drawing-engine/selection-box.ts:64](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/drawing-engine/selection-box.ts#L64)

#### Returns

`void`

***

### draw()

> **draw**(`deltaTime`): `void`

Defined in: [drawing-engine/selection-box.ts:35](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/drawing-engine/selection-box.ts#L35)

#### Parameters

##### deltaTime

`number`

#### Returns

`void`

#### Implementation of

[`DrawTask`](../interfaces/DrawTask.md).[`draw`](../interfaces/DrawTask.md#draw)

***

### drawWithContext()

> **drawWithContext**(`context`, `deltaTime`): `void`

Defined in: [drawing-engine/selection-box.ts:47](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/drawing-engine/selection-box.ts#L47)

#### Parameters

##### context

[`CanvasRenderingContext2D`](https://developer.mozilla.org/docs/Web/API/CanvasRenderingContext2D)

##### deltaTime

`number`

#### Returns

`void`

#### Implementation of

[`DrawTask`](../interfaces/DrawTask.md).[`drawWithContext`](../interfaces/DrawTask.md#drawwithcontext)

***

### startSelection()

> **startSelection**(): `void`

Defined in: [drawing-engine/selection-box.ts:60](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/drawing-engine/selection-box.ts#L60)

#### Returns

`void`
