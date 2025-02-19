[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / DefaultTouchStrategy

# Class: DefaultTouchStrategy

Defined in: [touch-strategy/touch-strategy.ts:21](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L21)

## Implements

- [`BoardTouchStrategy`](../interfaces/BoardTouchStrategy.md)
- [`TouchContext`](../interfaces/TouchContext.md)

## Constructors

### new DefaultTouchStrategy()

> **new DefaultTouchStrategy**(`canvas`, `inputObserver`, `alignCoordinateSystem`): [`DefaultTouchStrategy`](DefaultTouchStrategy.md)

Defined in: [touch-strategy/touch-strategy.ts:36](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L36)

#### Parameters

##### canvas

[`HTMLCanvasElement`](https://developer.mozilla.org/docs/Web/API/HTMLCanvasElement)

##### inputObserver

[`RawUserInputObservable`](RawUserInputObservable.md)

##### alignCoordinateSystem

`boolean` = `true`

#### Returns

[`DefaultTouchStrategy`](DefaultTouchStrategy.md)

## Accessors

### alignCoordinateSystem

#### Get Signature

> **get** **alignCoordinateSystem**(): `boolean`

Defined in: [touch-strategy/touch-strategy.ts:90](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L90)

##### Returns

`boolean`

#### Set Signature

> **set** **alignCoordinateSystem**(`alignCoordinateSystem`): `void`

Defined in: [touch-strategy/touch-strategy.ts:94](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L94)

##### Parameters

###### alignCoordinateSystem

`boolean`

##### Returns

`void`

#### Implementation of

[`BoardTouchStrategy`](../interfaces/BoardTouchStrategy.md).[`alignCoordinateSystem`](../interfaces/BoardTouchStrategy.md#aligncoordinatesystem)

***

### canvas

#### Get Signature

> **get** **canvas**(): [`HTMLCanvasElement`](https://developer.mozilla.org/docs/Web/API/HTMLCanvasElement)

Defined in: [touch-strategy/touch-strategy.ts:214](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L214)

##### Returns

[`HTMLCanvasElement`](https://developer.mozilla.org/docs/Web/API/HTMLCanvasElement)

#### Implementation of

[`TouchContext`](../interfaces/TouchContext.md).[`canvas`](../interfaces/TouchContext.md#canvas)

***

### disabled

#### Get Signature

> **get** **disabled**(): `boolean`

Defined in: [touch-strategy/touch-strategy.ts:86](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L86)

##### Returns

`boolean`

#### Implementation of

[`BoardTouchStrategy`](../interfaces/BoardTouchStrategy.md).[`disabled`](../interfaces/BoardTouchStrategy.md#disabled)

***

### panDisabled

#### Get Signature

> **get** **panDisabled**(): `boolean`

Defined in: [touch-strategy/touch-strategy.ts:98](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L98)

##### Returns

`boolean`

#### Set Signature

> **set** **panDisabled**(`panDisabled`): `void`

Defined in: [touch-strategy/touch-strategy.ts:102](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L102)

##### Parameters

###### panDisabled

`boolean`

##### Returns

`void`

#### Implementation of

[`BoardTouchStrategy`](../interfaces/BoardTouchStrategy.md).[`panDisabled`](../interfaces/BoardTouchStrategy.md#pandisabled)

***

### rotateDisabled

#### Get Signature

> **get** **rotateDisabled**(): `boolean`

Defined in: [touch-strategy/touch-strategy.ts:114](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L114)

##### Returns

`boolean`

#### Set Signature

> **set** **rotateDisabled**(`rotateDisabled`): `void`

Defined in: [touch-strategy/touch-strategy.ts:118](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L118)

##### Parameters

###### rotateDisabled

`boolean`

##### Returns

`void`

#### Implementation of

[`BoardTouchStrategy`](../interfaces/BoardTouchStrategy.md).[`rotateDisabled`](../interfaces/BoardTouchStrategy.md#rotatedisabled)

***

### touchStateMachine

#### Get Signature

> **get** **touchStateMachine**(): [`TouchSM`](TouchSM.md)

Defined in: [touch-strategy/touch-strategy.ts:47](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L47)

##### Returns

[`TouchSM`](TouchSM.md)

#### Implementation of

[`BoardTouchStrategy`](../interfaces/BoardTouchStrategy.md).[`touchStateMachine`](../interfaces/BoardTouchStrategy.md#touchstatemachine)

***

### zoomDisabled

#### Get Signature

> **get** **zoomDisabled**(): `boolean`

Defined in: [touch-strategy/touch-strategy.ts:106](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L106)

##### Returns

`boolean`

#### Set Signature

> **set** **zoomDisabled**(`zoomDisabled`): `void`

Defined in: [touch-strategy/touch-strategy.ts:110](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L110)

##### Parameters

###### zoomDisabled

`boolean`

##### Returns

`void`

#### Implementation of

[`BoardTouchStrategy`](../interfaces/BoardTouchStrategy.md).[`zoomDisabled`](../interfaces/BoardTouchStrategy.md#zoomdisabled)

## Methods

### addTouchPoints()

> **addTouchPoints**(`points`): `void`

Defined in: [touch-strategy/touch-strategy.ts:127](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L127)

#### Parameters

##### points

[`TouchPoints`](../type-aliases/TouchPoints.md)[]

#### Returns

`void`

#### Implementation of

[`TouchContext`](../interfaces/TouchContext.md).[`addTouchPoints`](../interfaces/TouchContext.md#addtouchpoints)

***

### bindListeners()

> **bindListeners**(): `void`

Defined in: [touch-strategy/touch-strategy.ts:51](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L51)

#### Returns

`void`

***

### disableStrategy()

> **disableStrategy**(): `void`

Defined in: [touch-strategy/touch-strategy.ts:66](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L66)

#### Returns

`void`

#### Implementation of

[`BoardTouchStrategy`](../interfaces/BoardTouchStrategy.md).[`disableStrategy`](../interfaces/BoardTouchStrategy.md#disablestrategy)

***

### enableStrategy()

> **enableStrategy**(): `void`

Defined in: [touch-strategy/touch-strategy.ts:62](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L62)

#### Returns

`void`

#### Implementation of

[`BoardTouchStrategy`](../interfaces/BoardTouchStrategy.md).[`enableStrategy`](../interfaces/BoardTouchStrategy.md#enablestrategy)

***

### getCurrentTouchPointsCount()

> **getCurrentTouchPointsCount**(): `number`

Defined in: [touch-strategy/touch-strategy.ts:122](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L122)

#### Returns

`number`

#### Implementation of

[`TouchContext`](../interfaces/TouchContext.md).[`getCurrentTouchPointsCount`](../interfaces/TouchContext.md#getcurrenttouchpointscount)

***

### getInitialTouchPointsPositions()

> **getInitialTouchPointsPositions**(`idents`): [`TouchPoints`](../type-aliases/TouchPoints.md)[]

Defined in: [touch-strategy/touch-strategy.ts:188](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L188)

#### Parameters

##### idents

`number`[]

#### Returns

[`TouchPoints`](../type-aliases/TouchPoints.md)[]

#### Implementation of

[`TouchContext`](../interfaces/TouchContext.md).[`getInitialTouchPointsPositions`](../interfaces/TouchContext.md#getinitialtouchpointspositions)

***

### notifyOnPan()

> **notifyOnPan**(`delta`): `void`

Defined in: [touch-strategy/touch-strategy.ts:206](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L206)

#### Parameters

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

[`TouchContext`](../interfaces/TouchContext.md).[`notifyOnPan`](../interfaces/TouchContext.md#notifyonpan)

***

### notifyOnZoom()

> **notifyOnZoom**(`zoomAmount`, `anchorPoint`): `void`

Defined in: [touch-strategy/touch-strategy.ts:210](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L210)

#### Parameters

##### zoomAmount

`number`

##### anchorPoint

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

[`TouchContext`](../interfaces/TouchContext.md).[`notifyOnZoom`](../interfaces/TouchContext.md#notifyonzoom)

***

### removeTouchPoints()

> **removeTouchPoints**(`identifiers`): `void`

Defined in: [touch-strategy/touch-strategy.ts:133](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L133)

#### Parameters

##### identifiers

`number`[]

#### Returns

`void`

#### Implementation of

[`TouchContext`](../interfaces/TouchContext.md).[`removeTouchPoints`](../interfaces/TouchContext.md#removetouchpoints)

***

### resetAttributes()

> **resetAttributes**(): `void`

Defined in: [touch-strategy/touch-strategy.ts:58](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L58)

#### Returns

`void`

***

### setUp()

> **setUp**(): `void`

Defined in: [touch-strategy/touch-strategy.ts:71](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L71)

#### Returns

`void`

#### Implementation of

[`BoardTouchStrategy`](../interfaces/BoardTouchStrategy.md).[`setUp`](../interfaces/BoardTouchStrategy.md#setup)

***

### tearDown()

> **tearDown**(): `void`

Defined in: [touch-strategy/touch-strategy.ts:78](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L78)

#### Returns

`void`

#### Implementation of

[`BoardTouchStrategy`](../interfaces/BoardTouchStrategy.md).[`tearDown`](../interfaces/BoardTouchStrategy.md#teardown)

***

### touchcancelHandler()

> **touchcancelHandler**(`e`): `void`

Defined in: [touch-strategy/touch-strategy.ts:154](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L154)

#### Parameters

##### e

[`TouchEvent`](https://developer.mozilla.org/docs/Web/API/TouchEvent)

#### Returns

`void`

***

### touchendHandler()

> **touchendHandler**(`e`): `void`

Defined in: [touch-strategy/touch-strategy.ts:165](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L165)

#### Parameters

##### e

[`TouchEvent`](https://developer.mozilla.org/docs/Web/API/TouchEvent)

#### Returns

`void`

***

### touchmoveHandler()

> **touchmoveHandler**(`e`): `void`

Defined in: [touch-strategy/touch-strategy.ts:176](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L176)

#### Parameters

##### e

[`TouchEvent`](https://developer.mozilla.org/docs/Web/API/TouchEvent)

#### Returns

`void`

***

### touchstartHandler()

> **touchstartHandler**(`e`): `void`

Defined in: [touch-strategy/touch-strategy.ts:141](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L141)

#### Parameters

##### e

[`TouchEvent`](https://developer.mozilla.org/docs/Web/API/TouchEvent)

#### Returns

`void`

***

### updateTouchPoints()

> **updateTouchPoints**(`pointsMoved`): `void`

Defined in: [touch-strategy/touch-strategy.ts:198](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/touch-strategy/touch-strategy.ts#L198)

#### Parameters

##### pointsMoved

[`TouchPoints`](../type-aliases/TouchPoints.md)[]

#### Returns

`void`

#### Implementation of

[`TouchContext`](../interfaces/TouchContext.md).[`updateTouchPoints`](../interfaces/TouchContext.md#updatetouchpoints)
