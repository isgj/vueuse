---
category: Sensors
---

# useDeviceLight

Reactive [DeviceLightEvent](https://developer.mozilla.org/en-US/docs/Web/API/DeviceLightEvent). Provide web developers with information from photo sensors or similar detectors about ambient light levels near the device. For example, this may be useful to adjust the screen's brightness based on the current ambient light level in order to save energy or provide better readability.

## Usage

```js
import { useDeviceLight } from '@vueuse/core'

const light = useDeviceLight()
```

| State | Type     | Description                                                                 |
| ----- | -------- | --------------------------------------------------------------------------- |
| light | `Number` | The level of the ambient light in [lux](https://en.wikipedia.org/wiki/Lux). |


<!--FOOTER_STARTS-->
## Type Declarations

```typescript
/**
 * Reactive DeviceLightEvent.
 *
 * @link https://vueuse.org/useDeviceLight
 * @param options
 */
export declare function useDeviceLight({
  window,
}?: ConfigurableWindow): Ref<number | null>
```

## Source

[Source](https://github.com/vueuse/vueuse/blob/main/packages/core/useDeviceLight/index.ts) • [Demo](https://github.com/vueuse/vueuse/blob/main/packages/core/useDeviceLight/demo.vue) • [Docs](https://github.com/vueuse/vueuse/blob/main/packages/core/useDeviceLight/index.md)


<!--FOOTER_ENDS-->
