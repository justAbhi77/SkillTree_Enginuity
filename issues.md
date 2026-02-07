## Unreal Engine Version Notes (5.3)

Due to changes in newer Unreal Engine versions (tested in UE 5.3), the following differences apply:

1. **Text Wrapping**
   - The `Wrap Text At` property cannot be set dynamically in **Wbp_SkillTree_Node** in UE 5.3.

2. **Runtime Float Curves**
   - Runtime evaluation of Float Curves is no longer supported in the same way.
   - This has been replaced with direct **Curve Float variable** usage instead.

3. **Soft Class References**
   - Soft Class References can no longer be asynchronously loaded in newer engine versions.

These changes are engine-level limitations/behavior changes and not issues with the course content itself.
