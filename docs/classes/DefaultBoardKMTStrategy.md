[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / DefaultBoardKMTStrategy

# Class: DefaultBoardKMTStrategy

Defined in: [kmt-strategy/kmt-strategy.ts:51](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L51)

## Implements

- [`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md)

## Constructors

### new DefaultBoardKMTStrategy()

> **new DefaultBoardKMTStrategy**(`canvas`, `eventTarget`, `inputObserver`, `selectionInputObserver`, `debugMode`, `alignCoordinateSystem`): [`DefaultBoardKMTStrategy`](DefaultBoardKMTStrategy.md)

Defined in: [kmt-strategy/kmt-strategy.ts:69](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L69)

#### Parameters

##### canvas

[`HTMLCanvasElement`](https://developer.mozilla.org/docs/Web/API/HTMLCanvasElement)

##### eventTarget

[`EventTargetWithPointerEvents`](../type-aliases/EventTargetWithPointerEvents.md)

##### inputObserver

[`RawUserInputObservable`](RawUserInputObservable.md)

##### selectionInputObserver

[`SelectionInputObserver`](SelectionInputObserver.md)

##### debugMode

`boolean` = `false`

##### alignCoordinateSystem

`boolean` = `true`

#### Returns

[`DefaultBoardKMTStrategy`](DefaultBoardKMTStrategy.md)

## Accessors

### alignCoordinateSystem

#### Get Signature

> **get** **alignCoordinateSystem**(): `boolean`

Defined in: [kmt-strategy/kmt-strategy.ts:138](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L138)

##### Returns

`boolean`

#### Set Signature

> **set** **alignCoordinateSystem**(`value`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:142](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L142)

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

Defined in: [kmt-strategy/kmt-strategy.ts:146](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L146)

##### Returns

[`HTMLCanvasElement`](https://developer.mozilla.org/docs/Web/API/HTMLCanvasElement)

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`canvas`](../interfaces/BoardKMTStrategy.md#canvas)

***

### debugMode

#### Get Signature

> **get** **debugMode**(): `boolean`

Defined in: [kmt-strategy/kmt-strategy.ts:122](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L122)

##### Returns

`boolean`

#### Set Signature

> **set** **debugMode**(`value`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:126](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L126)

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

Defined in: [kmt-strategy/kmt-strategy.ts:130](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L130)

##### Returns

`boolean`

#### Set Signature

> **set** **disabled**(`value`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:134](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L134)

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

Defined in: [kmt-strategy/kmt-strategy.ts:118](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L118)

##### Returns

[`Point`](../type-aliases/Point.md)

***

### inputObserver

#### Get Signature

> **get** **inputObserver**(): [`RawUserInputObservable`](RawUserInputObservable.md)

Defined in: [kmt-strategy/kmt-strategy.ts:150](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L150)

##### Returns

[`RawUserInputObservable`](RawUserInputObservable.md)

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`inputObserver`](../interfaces/BoardKMTStrategy.md#inputobserver)

***

### selectionInputObserver

#### Get Signature

> **get** **selectionInputObserver**(): [`SelectionInputObserver`](SelectionInputObserver.md)

Defined in: [kmt-strategy/kmt-strategy.ts:158](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L158)

##### Returns

[`SelectionInputObserver`](SelectionInputObserver.md)

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`selectionInputObserver`](../interfaces/BoardKMTStrategy.md#selectioninputobserver)

***

### stateMachine

#### Get Signature

> **get** **stateMachine**(): [`UserInputStateMachine`](UserInputStateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

Defined in: [kmt-strategy/kmt-strategy.ts:154](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L154)

##### Returns

[`UserInputStateMachine`](UserInputStateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`stateMachine`](../interfaces/BoardKMTStrategy.md#statemachine)

## Methods

### addEventListeners()

> **addEventListeners**(`eventTarget`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:166](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L166)

#### Parameters

##### eventTarget

[`EventTargetWithPointerEvents`](../type-aliases/EventTargetWithPointerEvents.md)

#### Returns

`void`

***

### bindFunctions()

> **bindFunctions**(): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:184](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L184)

#### Returns

`void`

***

### keypressHandler()

> **keypressHandler**(`e`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:249](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L249)

#### Parameters

##### e

[`KeyboardEvent`](https://developer.mozilla.org/docs/Web/API/KeyboardEvent)

#### Returns

`void`

***

### keyupHandler()

> **keyupHandler**(`e`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:260](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L260)

#### Parameters

##### e

[`KeyboardEvent`](https://developer.mozilla.org/docs/Web/API/KeyboardEvent)

#### Returns

`void`

***

### notifyOnPan()

> **notifyOnPan**(`delta`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:106](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L106)

#### Parameters

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### notifyOnZoom()

> **notifyOnZoom**(`zoomAmount`, `anchorPoint`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:110](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L110)

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

Defined in: [kmt-strategy/kmt-strategy.ts:193](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L193)

#### Parameters

##### e

[`MinimumPointerEvent`](../type-aliases/MinimumPointerEvent.md)

#### Returns

`void`

***

### pointerMoveHandler()

> **pointerMoveHandler**(`e`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:225](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L225)

#### Parameters

##### e

[`MinimumPointerEvent`](../type-aliases/MinimumPointerEvent.md)

#### Returns

`void`

***

### pointerUpHandler()

> **pointerUpHandler**(`e`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:209](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L209)

#### Parameters

##### e

[`MinimumPointerEvent`](../type-aliases/MinimumPointerEvent.md)

#### Returns

`void`

***

### scrollHandler()

> **scrollHandler**(`e`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:239](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L239)

#### Parameters

##### e

[`MinimumWheelEvent`](../type-aliases/MinimumWheelEvent.md)

#### Returns

`void`

***

### setInitialCursorPosition()

> **setInitialCursorPosition**(`position`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:114](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L114)

#### Parameters

##### position

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### setSelectionEndPoint()

> **setSelectionEndPoint**(`point`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:98](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L98)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### setSelectionStartPoint()

> **setSelectionStartPoint**(`point`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:102](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L102)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### setUp()

> **setUp**(): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:162](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L162)

#### Returns

`void`

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`setUp`](../interfaces/BoardKMTStrategy.md#setup)

***

### tearDown()

> **tearDown**(): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:175](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L175)

#### Returns

`void`

#### Implementation of

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md).[`tearDown`](../interfaces/BoardKMTStrategy.md#teardown)

***

### toggleSelectionBox()

> **toggleSelectionBox**(`value`): `void`

Defined in: [kmt-strategy/kmt-strategy.ts:94](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/kmt-strategy/kmt-strategy.ts#L94)

#### Parameters

##### value

`boolean`

#### Returns

`void`
