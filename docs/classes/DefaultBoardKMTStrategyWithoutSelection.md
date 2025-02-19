[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / DefaultBoardKMTStrategyWithoutSelection

# Class: DefaultBoardKMTStrategyWithoutSelection

Defined in: [kmt-strategy/kmt-strategy.ts:271](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L271)

## Implements

- [`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md)

## Constructors

### new DefaultBoardKMTStrategyWithoutSelection()

> **new DefaultBoardKMTStrategyWithoutSelection**(`canvas`, `eventTarget`, `inputObserver`, `debugMode`, `alignCoordinateSystem`): [`DefaultBoardKMTStrategyWithoutSelection`](DefaultBoardKMTStrategyWithoutSelection.md)

Defined in: [kmt-strategy/kmt-strategy.ts:289](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L289)

#### Parameters

##### canvas

[`HTMLCanvasElement`](https://developer.mozilla.org/docs/Web/API/HTMLCanvasElement)

##### eventTarget

[`EventTargetWithPointerEvents`](../type-aliases/EventTargetWithPointerEvents.md)

##### inputObserver

[`RawUserInputObservable`](RawUserInputObservable.md)

##### debugMode

`boolean` = `false`

##### alignCoordinateSystem

`boolean` = `true`

#### Returns

[`DefaultBoardKMTStrategyWithoutSelection`](DefaultBoardKMTStrategyWithoutSelection.md)

## Accessors

### alignCoordinateSystem

#### Get Signature

> **get** **alignCoordinateSystem**(): `boolean`

Defined in: [kmt-strategy/kmt-strategy.ts:357](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L357)

##### Returns

`boolean`

#### Set Signature

> **set** **alignCoordinateSystem**(`value`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:361](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L361)

##### Parameters

###### value

`boolean`

##### Returns

`void`

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`alignCoordinateSystem`](../interfaces/BoardKMTStrategy.md#aligncoordinatesystem)

***

### canvas

#### Get Signature

> **get** **canvas**(): [`HTMLCanvasElement`](https://developer.mozilla.org/docs/Web/API/HTMLCanvasElement)

Defined in: [kmt-strategy/kmt-strategy.ts:365](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L365)

##### Returns

[`HTMLCanvasElement`](https://developer.mozilla.org/docs/Web/API/HTMLCanvasElement)

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`canvas`](../interfaces/BoardKMTStrategy.md#canvas)

***

### debugMode

#### Get Signature

> **get** **debugMode**(): `boolean`

Defined in: [kmt-strategy/kmt-strategy.ts:341](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L341)

##### Returns

`boolean`

#### Set Signature

> **set** **debugMode**(`value`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:345](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L345)

##### Parameters

###### value

`boolean`

##### Returns

`void`

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`debugMode`](../interfaces/BoardKMTStrategy.md#debugmode)

***

### disabled

#### Get Signature

> **get** **disabled**(): `boolean`

Defined in: [kmt-strategy/kmt-strategy.ts:349](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L349)

##### Returns

`boolean`

#### Set Signature

> **set** **disabled**(`value`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:353](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L353)

##### Parameters

###### value

`boolean`

##### Returns

`void`

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`disabled`](../interfaces/BoardKMTStrategy.md#disabled)

***

### initialCursorPosition

#### Get Signature

> **get** **initialCursorPosition**(): [`Point`](../type-aliases/Point.md)

Defined in: [kmt-strategy/kmt-strategy.ts:337](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L337)

##### Returns

[`Point`](../type-aliases/Point.md)

***

### inputObserver

#### Get Signature

> **get** **inputObserver**(): [`RawUserInputObservable`](RawUserInputObservable.md)

Defined in: [kmt-strategy/kmt-strategy.ts:369](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L369)

##### Returns

[`RawUserInputObservable`](RawUserInputObservable.md)

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`inputObserver`](../interfaces/BoardKMTStrategy.md#inputobserver)

***

### selectionInputObserver

#### Get Signature

> **get** **selectionInputObserver**(): [`SelectionInputObserver`](SelectionInputObserver.md)

Defined in: [kmt-strategy/kmt-strategy.ts:377](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L377)

##### Returns

[`SelectionInputObserver`](SelectionInputObserver.md)

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`selectionInputObserver`](../interfaces/BoardKMTStrategy.md#selectioninputobserver)

***

### stateMachine

#### Get Signature

> **get** **stateMachine**(): [`UserInputStateMachine`](UserInputStateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

Defined in: [kmt-strategy/kmt-strategy.ts:373](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L373)

##### Returns

[`UserInputStateMachine`](UserInputStateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`stateMachine`](../interfaces/BoardKMTStrategy.md#statemachine)

## Methods

### addEventListeners()

> **addEventListeners**(`eventTarget`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:385](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L385)

#### Parameters

##### eventTarget

[`EventTargetWithPointerEvents`](../type-aliases/EventTargetWithPointerEvents.md)

#### Returns

`void`

***

### bindFunctions()

> **bindFunctions**(): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:403](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L403)

#### Returns

`void`

***

### keypressHandler()

> **keypressHandler**(`e`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:469](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L469)

#### Parameters

##### e

[`KeyboardEvent`](https://developer.mozilla.org/docs/Web/API/KeyboardEvent)

#### Returns

`void`

***

### keyupHandler()

> **keyupHandler**(`e`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:480](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L480)

#### Parameters

##### e

[`KeyboardEvent`](https://developer.mozilla.org/docs/Web/API/KeyboardEvent)

#### Returns

`void`

***

### notifyOnPan()

> **notifyOnPan**(`delta`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:325](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L325)

#### Parameters

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### notifyOnZoom()

> **notifyOnZoom**(`zoomAmount`, `anchorPoint`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:329](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L329)

#### Parameters

##### zoomAmount

`number`

##### anchorPoint

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### pointerDownHandler()

> **pointerDownHandler**(`e`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:412](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L412)

#### Parameters

##### e

[`MinimumPointerEvent`](../type-aliases/MinimumPointerEvent.md)

#### Returns

`void`

***

### pointerMoveHandler()

> **pointerMoveHandler**(`e`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:445](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L445)

#### Parameters

##### e

[`MinimumPointerEvent`](../type-aliases/MinimumPointerEvent.md)

#### Returns

`void`

***

### pointerUpHandler()

> **pointerUpHandler**(`e`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:429](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L429)

#### Parameters

##### e

[`MinimumPointerEvent`](../type-aliases/MinimumPointerEvent.md)

#### Returns

`void`

***

### scrollHandler()

> **scrollHandler**(`e`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:459](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L459)

#### Parameters

##### e

[`MinimumWheelEvent`](../type-aliases/MinimumWheelEvent.md)

#### Returns

`void`

***

### setInitialCursorPosition()

> **setInitialCursorPosition**(`position`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:333](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L333)

#### Parameters

##### position

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### setSelectionEndPoint()

> **setSelectionEndPoint**(`point`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:317](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L317)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### setSelectionStartPoint()

> **setSelectionStartPoint**(`point`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:321](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L321)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### setUp()

> **setUp**(): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:381](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L381)

#### Returns

`void`

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`setUp`](../interfaces/BoardKMTStrategy.md#setup)

***

### tearDown()

> **tearDown**(): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:394](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L394)

#### Returns

`void`

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`tearDown`](../interfaces/BoardKMTStrategy.md#teardown)

***

### toggleSelectionBox()

> **toggleSelectionBox**(`value`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:313](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/kmt-strategy/kmt-strategy.ts#L313)

#### Parameters

##### value

`boolean`

#### Returns

`void`
