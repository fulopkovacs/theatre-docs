<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@theatre/react](./react.md) &gt; [usePrismWithoutReRender](./react.useprismwithoutrerender.md)

## usePrismWithoutReRender() function

This makes sure the prism derivation remains hot as long as the component calling the hook is alive, but it does not return the value of the derivation, and it does not re-render the component if the value of the derivation changes.

Use this hook if you plan to read a derivation in a useEffect() call, without the derivation causing your element to re-render.

<b>Signature:</b>

```typescript
export declare function usePrismWithoutReRender<T>(fn: () => T, deps: unknown[]): IDerivation<T>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  fn | () =&gt; T |  |
|  deps | unknown\[\] |  |

<b>Returns:</b>

[IDerivation](./dataverse.iderivation.md)<!-- -->&lt;T&gt;
