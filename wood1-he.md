### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# אמנו את הסוכן

## Step 1
אמנו את הסוכן לזהות מהו עץ על ידי ``||haiInputs: classifying||`` של ``||hai: oak log||`` כעץ. גררו את הבלוק ``||haiInputs: classify as wood||`` מתוך ארגז הכלים שמשמאל והניחו אותו בתוך הבלוק ``||training module||`` שבסביבת העבודה מימין. לאחר מכן, גררו את הבלוק ``||hai: oak log||`` מארגז הכלים והניחו אותו בתוך הבלוק ``||haiInputs: classify as wood||``. לחצו על הנורה לקבלת עזרה, או לחצו על כפתור ההפעלה הירוק כשאתם מוכנים להמשיך.

#### ~ tutorialhint 
גררו את הבלוק ``||haiInputs: classify as wood||`` מתוך ארגז הכלים שמשמאל והניחו אותו בתוך הבלוק ``||training module||`` שבסביבת העבודה מימין. לאחר מכן, גררו את הבלוק ``||hai: oak log||`` מארגז הכלים והניחו אותו בתוך הבלוק ``||haiInputs: classify as wood||``.
```ghost

hai.classifyWood(hai.ghostBlock())
hai.classifyWood(hai.logOak())
hai.classifyWood(hai.grass()) 
hai.classifyWood(hai.lava())
hai.classifyWood(hai.soulSand())
hai.trainingStart()
```
```template
hai.trainingStart(function () {
})

```
```package
hai2025-ts=github:ReWrite-Media/hai2025-ts
```
