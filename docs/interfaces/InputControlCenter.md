[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / InputControlCenter

# Interface: InputControlCenter

Defined in: [control-center/control-center.ts:8](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/control-center.ts#L8)

## Properties

### limitEntireViewPort

> **limitEntireViewPort**: `boolean`

Defined in: [control-center/control-center.ts:12](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/control-center.ts#L12)

## Methods

### notifyPanInput()

> **notifyPanInput**(`diff`): `void`

Defined in: [control-center/control-center.ts:13](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/control-center.ts#L13)

#### Parameters

##### diff

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### notifyRotationInput()

> **notifyRotationInput**(`deltaRotation`): `void`

Defined in: [control-center/control-center.ts:15](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/control-center.ts#L15)

#### Parameters

##### deltaRotation

`number`

#### Returns

`void`

***

### notifyZoomInput()

> **notifyZoomInput**(`deltaZoomAmount`, `anchorPoint`): `void`

Defined in: [control-center/control-center.ts:14](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/control-center.ts#L14)

#### Parameters

##### deltaZoomAmount

`number`

##### anchorPoint

[`Point`](../type-aliases/Point.md)

#### Returns

`void`
