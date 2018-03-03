## WalkerStepTo

Easier version of [WalkerDiff](/api-native-functions/walkerdiff.md)

Syntax: `WalkerStepTo(wa,wb)`

* `wa` walker that will be moved towards `wb`
* `wb` target walker or spot index for direction

Returns: Function returns the same step that walker `wa` performed inside the function.

Notes: If `wa` is on the opposite side of `wb`, than `STEP_NOTHING` is performed and returned.

Example: `WalkerStepTo(player,GetCursor())`, moves player towards the cursor

See also: [WalkerDiff](/api-native-functions/walkerdiff.md)

