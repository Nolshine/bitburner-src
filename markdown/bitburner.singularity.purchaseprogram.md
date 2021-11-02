<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [Singularity](./bitburner.singularity.md) &gt; [purchaseProgram](./bitburner.singularity.purchaseprogram.md)

## Singularity.purchaseProgram() method

If you are not in BitNode-4, then you must have Level 1 of Source-File 4 in order to use this function and the RAM cost is doubled.

This function allows you to automatically purchase programs. You MUST have a TOR router in order to use this function. The cost of purchasing programs using this function is the same as if you were purchasing them through the Dark Web using the Terminal buy command.

<b>Signature:</b>

```typescript
purchaseProgram(programName: Programs): boolean;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  programName | [Programs](./bitburner.programs.md) | Name of program to purchase. |

<b>Returns:</b>

boolean

True if the specified program is purchased, and false otherwise.

## Remarks

Singularity - Level 1

## Example


```ts
purchaseProgram("brutessh.exe");
```
