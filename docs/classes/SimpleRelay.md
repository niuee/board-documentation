[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / SimpleRelay

# Class: SimpleRelay

Defined in: [control-center/control-center.ts:18](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/control-center.ts#L18)

## Implements

- [`InputControlCenter`](../interfaces/InputControlCenter.md)

## Constructors

### new SimpleRelay()

> **new SimpleRelay**(`panHandler`, `zoomHandler`, `rotationHandler`, `camera`): [`SimpleRelay`](SimpleRelay.md)

Defined in: [control-center/control-center.ts:25](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/control-center.ts#L25)

#### Parameters

##### panHandler

[`PanController`](../interfaces/PanController.md)

##### zoomHandler

[`ZoomController`](../interfaces/ZoomController.md)

##### rotationHandler

[`RotationController`](../interfaces/RotationController.md)

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md) = `...`

#### Returns

[`SimpleRelay`](SimpleRelay.md)

## Accessors

### limitEntireViewPort

#### Get Signature

> **get** **limitEntireViewPort**(): `boolean`

Defined in: [control-center/control-center.ts:44](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/control-center.ts#L44)

##### Returns

`boolean`

#### Set Signature

> **set** **limitEntireViewPort**(`limit`): `void`

Defined in: [control-center/control-center.ts:48](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/control-center.ts#L48)

##### Parameters

###### limit

`boolean`

##### Returns

`void`

#### Implementation of

[`InputControlCenter`](../interfaces/InputControlCenter.md).[`limitEntireViewPort`](../interfaces/InputControlCenter.md#limitentireviewport)

***

### panController

#### Get Signature

> **get** **panController**(): [`PanController`](../interfaces/PanController.md)

Defined in: [control-center/control-center.ts:32](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/control-center.ts#L32)

##### Returns

[`PanController`](../interfaces/PanController.md)

***

### rotationController

#### Get Signature

> **get** **rotationController**(): [`RotationController`](../interfaces/RotationController.md)

Defined in: [control-center/control-center.ts:40](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/control-center.ts#L40)

##### Returns

[`RotationController`](../interfaces/RotationController.md)

***

### zoomController

#### Get Signature

> **get** **zoomController**(): [`ZoomController`](../interfaces/ZoomController.md)

Defined in: [control-center/control-center.ts:36](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/control-center.ts#L36)

##### Returns

[`ZoomController`](../interfaces/ZoomController.md)

## Methods

### notifyPanInput()

> **notifyPanInput**(`diff`): `void`

Defined in: [control-center/control-center.ts:52](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/control-center.ts#L52)

#### Parameters

##### diff

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

[`InputControlCenter`](../interfaces/InputControlCenter.md).[`notifyPanInput`](../interfaces/InputControlCenter.md#notifypaninput)

***

### notifyRotationInput()

> **notifyRotationInput**(`deltaRotation`): `void`

Defined in: [control-center/control-center.ts:62](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/control-center.ts#L62)

#### Parameters

##### deltaRotation

`number`

#### Returns

`void`

#### Implementation of

[`InputControlCenter`](../interfaces/InputControlCenter.md).[`notifyRotationInput`](../interfaces/InputControlCenter.md#notifyrotationinput)

***

### notifyZoomInput()

> **notifyZoomInput**(`deltaZoomAmount`, `anchorPoint`): `void`

Defined in: [control-center/control-center.ts:57](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/control-center.ts#L57)

#### Parameters

##### deltaZoomAmount

`number`

##### anchorPoint

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

[`InputControlCenter`](../interfaces/InputControlCenter.md).[`notifyZoomInput`](../interfaces/InputControlCenter.md#notifyzoominput)
