# Datapack Advancement (*)

> This is part of the [Style Guideline](./style_guideline.md), Failing to follow this will not affect the verification process.

1. Compare the content of the file `/data/global/advancements/root.json` with [this one](./style_datapack_advancement.md#1-root-advancement).  
If it isn't the same then they have failed to follow this properly.

2. Determine whether this datapack uses the normal syntax or the standalone datapack syntax.
    1. If use normal syntax, check where the [Datapack Node](./style_datapack_advancement.md#3-datapack-advancement) file is.  
    if it's inside `/data/global/advancements/` directory, They have failed to follow this properly.
    2. If use standalone datapack syntax, check where the [Datapack Node](./style_datapack_advancement.md#3-datapack-advancement) file is.  
    if it's **not** inside `/data/global/advancements/standalone` directory, They have failed to follow this properly.

3. Check [Namespace Node](./style_datapack_advancement.md#2-namespace-advancement) file. This file **must** contain information about the creator of the datapack only. Any information besides that (i.e. datapack name) will mean they have failed to follow this properly.
