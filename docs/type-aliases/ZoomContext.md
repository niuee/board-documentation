[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / ZoomContext

# Type Alias: ZoomContext

> **ZoomContext**: `object`

Defined in: [control-center/zoom-control-state-machine.ts:40](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/zoom-control-state-machine.ts#L40)

## Type declaration

### zoomBy()

> **zoomBy**: (`delta`) => `void`

#### Parameters

##### delta

`number`

#### Returns

`void`

### zoomByAt()

> **zoomByAt**: (`delta`, `at`) => `void`

#### Parameters

##### delta

`number`

##### at

[`Point`](Point.md)

#### Returns

`void`

### zoomByAtWorld()

> **zoomByAtWorld**: (`delta`, `at`) => `void`

#### Parameters

##### delta

`number`

##### at

[`Point`](Point.md)

#### Returns

`void`

### zoomTo()

> **zoomTo**: (`targetZoom`) => `void`

#### Parameters

##### targetZoom

`number`

#### Returns

`void`

### zoomToAt()

> **zoomToAt**: (`targetZoom`, `at`) => `void`

#### Parameters

##### targetZoom

`number`

##### at

[`Point`](Point.md)

#### Returns

`void`

### zoomToAtWorld()

> **zoomToAtWorld**: (`targetZoom`, `at`) => `void`

#### Parameters

##### targetZoom

`number`

##### at

[`Point`](Point.md)

#### Returns

`void`
