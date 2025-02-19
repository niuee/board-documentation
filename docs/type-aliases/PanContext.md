[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / PanContext

# Type Alias: PanContext

> **PanContext**: `object`

Defined in: [control-center/pan-control-state-machine.ts:27](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/control-center/pan-control-state-machine.ts#L27)

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
