[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / Container

# Class: Container

Defined in: [drawing-engine/driver.ts:7](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/drawing-engine/driver.ts#L7)

## Implements

- [`DrawTask`](../interfaces/DrawTask.md)

## Constructors

### new Container()

> **new Container**(`context`): [`Container`](Container.md)

Defined in: [drawing-engine/driver.ts:14](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/drawing-engine/driver.ts#L14)

#### Parameters

##### context

[`CanvasRenderingContext2D`](https://developer.mozilla.org/docs/Web/API/CanvasRenderingContext2D)

#### Returns

[`Container`](Container.md)

## Accessors

### position

#### Get Signature

> **get** **position**(): [`Point`](../type-aliases/Point.md)

Defined in: [drawing-engine/driver.ts:26](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/drawing-engine/driver.ts#L26)

##### Returns

[`Point`](../type-aliases/Point.md)

#### Set Signature

> **set** **position**(`position`): `void`

Defined in: [drawing-engine/driver.ts:22](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/drawing-engine/driver.ts#L22)

##### Parameters

###### position

[`Point`](../type-aliases/Point.md)

##### Returns

`void`

## Methods

### addDrawTask()

> **addDrawTask**(`task`): `void`

Defined in: [drawing-engine/driver.ts:30](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/drawing-engine/driver.ts#L30)

#### Parameters

##### task

[`DrawTask`](../interfaces/DrawTask.md)

#### Returns

`void`

***

### draw()

> **draw**(`deltaTime`): `void`

Defined in: [drawing-engine/driver.ts:45](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/drawing-engine/driver.ts#L45)

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

Defined in: [drawing-engine/driver.ts:34](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/drawing-engine/driver.ts#L34)

#### Parameters

##### context

[`CanvasRenderingContext2D`](https://developer.mozilla.org/docs/Web/API/CanvasRenderingContext2D)

##### deltaTime

`number`

#### Returns

`void`

#### Implementation of

[`DrawTask`](../interfaces/DrawTask.md).[`drawWithContext`](../interfaces/DrawTask.md#drawwithcontext)
