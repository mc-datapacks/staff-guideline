## Custom Model ID (***)

> This step can be skip if the datapack does not required resourcepack to play.

1. Check the `ID` of the model and the `ID` that datapacker claim using [https://mc-datapacks.web.app](https://mc-datapacks.web.app/custom_model_id)

![](./review/correct_cmd_usage.png)
> This passed because the correct ID is used and it followed the convention correctly.

![](./review/incorrect_cmd_usage.png)
> Wrong `ID`, this should be `808` because Boomber claim the ID of `808` not `82`.

![](./review/incorrect_cmd_usage_2.png)
> There was no attempt at following the convention here at all.

2. Check for consistency of the ID with the datapack.

![](./review/inconsistent_cmd_usage.png)
> The datapack use the ID of `1` while the resourcepack use the ID of `808`