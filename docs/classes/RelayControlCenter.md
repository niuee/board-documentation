[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / RelayControlCenter

# Class: RelayControlCenter

Defined in: [control-center/simple-relay.ts:11](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/control-center/simple-relay.ts#L11)

## Implements

- [`InputControlCenter`](../interfaces/InputControlCenter.md)

## Constructors

### new RelayControlCenter()

> **new RelayControlCenter**(`panStateMachine`, `zoomStateMachine`): [`RelayControlCenter`](RelayControlCenter.md)

Defined in: [control-center/simple-relay.ts:16](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/control-center/simple-relay.ts#L16)

#### Parameters

##### panStateMachine

[`PanControlStateMachine`](PanControlStateMachine.md)

##### zoomStateMachine

[`ZoomControlStateMachine`](ZoomControlStateMachine.md)

#### Returns

[`RelayControlCenter`](RelayControlCenter.md)

## Accessors

### limitEntireViewPort

#### Get Signature

> **get** **limitEntireViewPort**(): `boolean`

Defined in: [control-center/simple-relay.ts:21](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/control-center/simple-relay.ts#L21)

##### Returns

`boolean`

#### Set Signature

> **set** **limitEntireViewPort**(`limit`): `void`

Defined in: [control-center/simple-relay.ts:25](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/control-center/simple-relay.ts#L25)

##### Parameters

###### limit

`boolean`

##### Returns

`void`

#### Implementation of

[`InputControlCenter`](../interfaces/InputControlCenter.md).[`limitEntireViewPort`](../interfaces/InputControlCenter.md#limitentireviewport)

## Methods

### initatePanTransition()

> **initatePanTransition**(): `void`

Defined in: [control-center/simple-relay.ts:53](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/control-center/simple-relay.ts#L53)

#### Returns

`void`

***

### initateZoomTransition()

> **initateZoomTransition**(): `void`

Defined in: [control-center/simple-relay.ts:57](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/control-center/simple-relay.ts#L57)

#### Returns

`void`

***

### notifyPanInput()

> **notifyPanInput**(`delta`): `void`

Defined in: [control-center/simple-relay.ts:33](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/control-center/simple-relay.ts#L33)

#### Parameters

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

[`InputControlCenter`](../interfaces/InputControlCenter.md).[`notifyPanInput`](../interfaces/InputControlCenter.md#notifypaninput)

***

### notifyPanToAnimationInput()

> **notifyPanToAnimationInput**(`target`): `void`

Defined in: [control-center/simple-relay.ts:29](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/control-center/simple-relay.ts#L29)

#### Parameters

##### target

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### notifyRotationInput()

> **notifyRotationInput**(`delta`): `void`

Defined in: [control-center/simple-relay.ts:49](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/control-center/simple-relay.ts#L49)

#### Parameters

##### delta

`number`

#### Returns

`void`

#### Implementation of

[`InputControlCenter`](../interfaces/InputControlCenter.md).[`notifyRotationInput`](../interfaces/InputControlCenter.md#notifyrotationinput)

***

### notifyZoomInput()

> **notifyZoomInput**(`delta`, `at`): `void`

Defined in: [control-center/simple-relay.ts:37](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/control-center/simple-relay.ts#L37)

#### Parameters

##### delta

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

[`InputControlCenter`](../interfaces/InputControlCenter.md).[`notifyZoomInput`](../interfaces/InputControlCenter.md#notifyzoominput)

***

### notifyZoomInputAnimation()

> **notifyZoomInputAnimation**(`targetZoom`, `at`): `void`

Defined in: [control-center/simple-relay.ts:41](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/control-center/simple-relay.ts#L41)

#### Parameters

##### targetZoom

`number`

##### at

[`Point`](../type-aliases/Point.md) = `...`

#### Returns

`void`

***

### notifyZoomInputAnimationWorld()

> **notifyZoomInputAnimationWorld**(`targetZoom`, `at`): `void`

Defined in: [control-center/simple-relay.ts:45](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/control-center/simple-relay.ts#L45)

#### Parameters

##### targetZoom

`number`

##### at

[`Point`](../type-aliases/Point.md) = `...`

#### Returns

`void`
