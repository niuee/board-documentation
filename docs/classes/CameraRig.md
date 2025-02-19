[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / CameraRig

# Class: CameraRig

Defined in: [control-center/simple-relay.ts:62](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L62)

## Implements

- [`PanContext`](../type-aliases/PanContext.md)
- [`ZoomContext`](../type-aliases/ZoomContext.md)

## Constructors

### new CameraRig()

> **new CameraRig**(`config`, `camera`): [`CameraRig`](CameraRig.md)

Defined in: [control-center/simple-relay.ts:76](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L76)

#### Parameters

##### config

[`PanHandlerConfig`](../type-aliases/PanHandlerConfig.md) & [`BaseZoomHandlerConfig`](../type-aliases/BaseZoomHandlerConfig.md)

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md) = `...`

#### Returns

[`CameraRig`](CameraRig.md)

## Accessors

### camera

#### Get Signature

> **get** **camera**(): [`BoardCamera`](../interfaces/BoardCamera.md)

Defined in: [control-center/simple-relay.ts:130](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L130)

##### Returns

[`BoardCamera`](../interfaces/BoardCamera.md)

#### Implementation of

`PanContext.camera`

***

### config

#### Get Signature

> **get** **config**(): [`PanHandlerConfig`](../type-aliases/PanHandlerConfig.md) & [`BaseZoomHandlerConfig`](../type-aliases/BaseZoomHandlerConfig.md)

Defined in: [control-center/simple-relay.ts:134](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L134)

##### Returns

[`PanHandlerConfig`](../type-aliases/PanHandlerConfig.md) & [`BaseZoomHandlerConfig`](../type-aliases/BaseZoomHandlerConfig.md)

#### Set Signature

> **set** **config**(`config`): `void`

Defined in: [control-center/simple-relay.ts:138](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L138)

##### Parameters

###### config

[`CameraRigConfig`](../type-aliases/CameraRigConfig.md)

##### Returns

`void`

***

### limitEntireViewPort

#### Get Signature

> **get** **limitEntireViewPort**(): `boolean`

Defined in: [control-center/simple-relay.ts:126](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L126)

##### Returns

`boolean`

#### Set Signature

> **set** **limitEntireViewPort**(`limit`): `void`

Defined in: [control-center/simple-relay.ts:122](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L122)

##### Parameters

###### limit

`boolean`

##### Returns

`void`

#### Implementation of

`PanContext.limitEntireViewPort`

## Methods

### configure()

> **configure**(`config`): `void`

Defined in: [control-center/simple-relay.ts:142](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L142)

#### Parameters

##### config

[`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`CameraRigConfig`](../type-aliases/CameraRigConfig.md)\>

#### Returns

`void`

***

### panBy()

> **panBy**(`delta`): `void`

Defined in: [control-center/simple-relay.ts:112](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L112)

#### Parameters

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

`PanContext.panBy`

***

### panTo()

> **panTo**(`target`): `void`

Defined in: [control-center/simple-relay.ts:117](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L117)

#### Parameters

##### target

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

`PanContext.panTo`

***

### zoomBy()

> **zoomBy**(`delta`): `void`

Defined in: [control-center/simple-relay.ts:100](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L100)

#### Parameters

##### delta

`number`

#### Returns

`void`

#### Implementation of

`ZoomContext.zoomBy`

***

### zoomByAt()

> **zoomByAt**(`delta`, `at`): `void`

Defined in: [control-center/simple-relay.ts:92](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L92)

#### Parameters

##### delta

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

`ZoomContext.zoomByAt`

***

### zoomByAtWorld()

> **zoomByAtWorld**(`delta`, `at`): `void`

Defined in: [control-center/simple-relay.ts:108](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L108)

#### Parameters

##### delta

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

`ZoomContext.zoomByAtWorld`

***

### zoomTo()

> **zoomTo**(`targetZoom`): `void`

Defined in: [control-center/simple-relay.ts:96](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L96)

#### Parameters

##### targetZoom

`number`

#### Returns

`void`

#### Implementation of

`ZoomContext.zoomTo`

***

### zoomToAt()

> **zoomToAt**(`targetZoom`, `at`): `void`

Defined in: [control-center/simple-relay.ts:88](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L88)

#### Parameters

##### targetZoom

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

`ZoomContext.zoomToAt`

***

### zoomToAtWorld()

> **zoomToAtWorld**(`targetZoom`, `at`): `void`

Defined in: [control-center/simple-relay.ts:104](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/simple-relay.ts#L104)

#### Parameters

##### targetZoom

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

`ZoomContext.zoomToAtWorld`
