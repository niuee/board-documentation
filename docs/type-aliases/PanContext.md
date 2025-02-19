[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / PanContext

# Type Alias: PanContext

> **PanContext**: `object`

Defined in: [control-center/pan-control-state-machine.ts:27](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/pan-control-state-machine.ts#L27)

## Type declaration

### camera

> **camera**: [`BoardCamera`](../interfaces/BoardCamera.md)

### limitEntireViewPort

> **limitEntireViewPort**: `boolean`

### panBy()

> **panBy**: (`delta`) => `void`

#### Parameters

##### delta

[`Point`](Point.md)

#### Returns

`void`

### panTo()

> **panTo**: (`target`) => `void`

#### Parameters

##### target

[`Point`](Point.md)

#### Returns

`void`
