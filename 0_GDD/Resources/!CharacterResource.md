The general component for a Characters Resource (that is something that is consumed to do other things, such as health to continue being alive or stamina to perform actions)

[float] Current Value
[float] MaximumValue

[UnitStat] RegeneratedPerTick


- Gain(float Amount)
- Use(float Amount)
- [bool] HasAmount(float Value)
- Modify(float value)
- ResourceRegenTick(float oldVale, float newValue)
- ResourceChanged(float oldValue, float newValue)
- ResourceFull()
- ResourceEmpty()
- Restore()
- EnableRegen()
- DisableRegen()
- Get()
- [float] GetAsPercent(float percentage)
  