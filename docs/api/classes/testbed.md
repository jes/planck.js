[Planck.js API Doc](../README.md) › [Globals](../globals.md) › [Testbed](testbed.md)

# Class: Testbed

## Hierarchy

* **Testbed**

## Index

### Properties

* [activeKeys](testbed.md#activekeys)
* [background](testbed.md#background)
* [height](testbed.md#height)
* [hz](testbed.md#hz)
* [mouseForce](testbed.md#optional-mouseforce)
* [ratio](testbed.md#ratio)
* [scaleY](testbed.md#scaley)
* [speed](testbed.md#speed)
* [width](testbed.md#width)
* [x](testbed.md#x)
* [y](testbed.md#y)

### Methods

* [color](testbed.md#color)
* [drawAABB](testbed.md#abstract-drawaabb)
* [drawCircle](testbed.md#abstract-drawcircle)
* [drawEdge](testbed.md#abstract-drawedge)
* [drawPoint](testbed.md#abstract-drawpoint)
* [drawPolygon](testbed.md#abstract-drawpolygon)
* [drawSegment](testbed.md#abstract-drawsegment)
* [findAll](testbed.md#abstract-findall)
* [findOne](testbed.md#abstract-findone)
* [info](testbed.md#info)
* [keydown](testbed.md#keydown)
* [keyup](testbed.md#keyup)
* [start](testbed.md#abstract-start)
* [status](testbed.md#status)
* [step](testbed.md#step)
* [mount](testbed.md#static-mount)

## Properties

###  activeKeys

• **activeKeys**: *[ActiveKeys](../globals.md#activekeys)*

*Defined in [src/util/Testbed.ts:51](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L51)*

___

###  background

• **background**: *string* = "#222222"

*Defined in [src/util/Testbed.ts:48](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L48)*

___

###  height

• **height**: *number* = 60

*Defined in [src/util/Testbed.ts:31](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L31)*

World viewbox height.

___

###  hz

• **hz**: *number* = 60

*Defined in [src/util/Testbed.ts:42](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L42)*

World simulation step frequency

___

### `Optional` mouseForce

• **mouseForce**? : *number*

*Defined in [src/util/Testbed.ts:50](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L50)*

___

###  ratio

• **ratio**: *number* = 16

*Defined in [src/util/Testbed.ts:47](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L47)*

___

###  scaleY

• **scaleY**: *number* = -1

*Defined in [src/util/Testbed.ts:39](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L39)*

___

###  speed

• **speed**: *number* = 1

*Defined in [src/util/Testbed.ts:45](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L45)*

World simulation speed, default is 1

___

###  width

• **width**: *number* = 80

*Defined in [src/util/Testbed.ts:28](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L28)*

World viewbox width.

___

###  x

• **x**: *number* = 0

*Defined in [src/util/Testbed.ts:34](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L34)*

World viewbox center vertical offset.

___

###  y

• **y**: *number* = -10

*Defined in [src/util/Testbed.ts:37](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L37)*

World viewbox center horizontal offset.

## Methods

###  color

▸ **color**(`r`: number, `g`: number, `b`: number): *string*

*Defined in [src/util/Testbed.ts:107](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L107)*

**Parameters:**

Name | Type |
------ | ------ |
`r` | number |
`g` | number |
`b` | number |

**Returns:** *string*

___

### `Abstract` drawAABB

▸ **drawAABB**(`aabb`: [AABBValue](../interfaces/aabbvalue.md), `color`: string): *void*

*Defined in [src/util/Testbed.ts:119](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L119)*

**Parameters:**

Name | Type |
------ | ------ |
`aabb` | [AABBValue](../interfaces/aabbvalue.md) |
`color` | string |

**Returns:** *void*

___

### `Abstract` drawCircle

▸ **drawCircle**(`p`: object, `r`: number, `color`: string): *void*

*Defined in [src/util/Testbed.ts:115](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L115)*

**Parameters:**

▪ **p**: *object*

Name | Type |
------ | ------ |
`x` | number |
`y` | number |

▪ **r**: *number*

▪ **color**: *string*

**Returns:** *void*

___

### `Abstract` drawEdge

▸ **drawEdge**(`a`: object, `b`: object, `color`: string): *void*

*Defined in [src/util/Testbed.ts:116](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L116)*

**Parameters:**

▪ **a**: *object*

Name | Type |
------ | ------ |
`x` | number |
`y` | number |

▪ **b**: *object*

Name | Type |
------ | ------ |
`x` | number |
`y` | number |

▪ **color**: *string*

**Returns:** *void*

___

### `Abstract` drawPoint

▸ **drawPoint**(`p`: object, `r`: any, `color`: string): *void*

*Defined in [src/util/Testbed.ts:114](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L114)*

**Parameters:**

▪ **p**: *object*

Name | Type |
------ | ------ |
`x` | number |
`y` | number |

▪ **r**: *any*

▪ **color**: *string*

**Returns:** *void*

___

### `Abstract` drawPolygon

▸ **drawPolygon**(`points`: Array‹object›, `color`: string): *void*

*Defined in [src/util/Testbed.ts:118](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L118)*

**Parameters:**

Name | Type |
------ | ------ |
`points` | Array‹object› |
`color` | string |

**Returns:** *void*

___

### `Abstract` drawSegment

▸ **drawSegment**(`a`: object, `b`: object, `color`: string): *void*

*Defined in [src/util/Testbed.ts:117](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L117)*

**Parameters:**

▪ **a**: *object*

Name | Type |
------ | ------ |
`x` | number |
`y` | number |

▪ **b**: *object*

Name | Type |
------ | ------ |
`x` | number |
`y` | number |

▪ **color**: *string*

**Returns:** *void*

___

### `Abstract` findAll

▸ **findAll**(`query`: string): *([Fixture](fixture.md)‹› | [Body](body.md)‹› | [Joint](joint.md)‹›)[]*

*Defined in [src/util/Testbed.ts:136](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L136)*

**Parameters:**

Name | Type |
------ | ------ |
`query` | string |

**Returns:** *([Fixture](fixture.md)‹› | [Body](body.md)‹› | [Joint](joint.md)‹›)[]*

___

### `Abstract` findOne

▸ **findOne**(`query`: string): *[Fixture](fixture.md)‹› | [Body](body.md)‹› | [Joint](joint.md)‹›*

*Defined in [src/util/Testbed.ts:135](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L135)*

**Parameters:**

Name | Type |
------ | ------ |
`query` | string |

**Returns:** *[Fixture](fixture.md)‹› | [Body](body.md)‹› | [Joint](joint.md)‹›*

___

###  info

▸ **info**(`text`: string): *void*

*Defined in [src/util/Testbed.ts:103](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L103)*

**Parameters:**

Name | Type |
------ | ------ |
`text` | string |

**Returns:** *void*

___

###  keydown

▸ **keydown**(`keyCode`: number, `label`: string): *void*

*Defined in [src/util/Testbed.ts:59](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L59)*

callback, to be implemented by user

**Parameters:**

Name | Type |
------ | ------ |
`keyCode` | number |
`label` | string |

**Returns:** *void*

___

###  keyup

▸ **keyup**(`keyCode`: number, `label`: string): *void*

*Defined in [src/util/Testbed.ts:64](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L64)*

callback, to be implemented by user

**Parameters:**

Name | Type |
------ | ------ |
`keyCode` | number |
`label` | string |

**Returns:** *void*

___

### `Abstract` start

▸ **start**(`world`: World): *void*

*Defined in [src/util/Testbed.ts:121](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L121)*

**Parameters:**

Name | Type |
------ | ------ |
`world` | World |

**Returns:** *void*

___

###  status

▸ **status**(`name`: string, `value`: any): *void*

*Defined in [src/util/Testbed.ts:71](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L71)*

**Parameters:**

Name | Type |
------ | ------ |
`name` | string |
`value` | any |

**Returns:** *void*

▸ **status**(`value`: object | string): *void*

*Defined in [src/util/Testbed.ts:72](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L72)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | object &#124; string |

**Returns:** *void*

___

###  step

▸ **step**(`dt`: number, `t`: number): *void*

*Defined in [src/util/Testbed.ts:54](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L54)*

callback, to be implemented by user

**Parameters:**

Name | Type |
------ | ------ |
`dt` | number |
`t` | number |

**Returns:** *void*

___

### `Static` mount

▸ **mount**(`options?`: [TestbedMountOptions](../globals.md#testbedmountoptions)): *Testbed*

*Defined in [src/util/Testbed.ts:23](https://github.com/shakiba/planck.js/blob/ae24904/src/util/Testbed.ts#L23)*

**Parameters:**

Name | Type |
------ | ------ |
`options?` | [TestbedMountOptions](../globals.md#testbedmountoptions) |

**Returns:** *Testbed*