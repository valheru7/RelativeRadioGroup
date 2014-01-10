RelativeRadioGroup
==================

Android RelativeRadioGroup

Why?
====

RadioGroup by default extends LinearLayout. Sometimes you need to order your radio buttons in a different layout other than in a straight line.

What?
=====

Extending RadioGroup from RelativeLayout instead allows for this.

Some details as to what was changed can be found at this stackoverflow post: http://stackoverflow.com/questions/6320125/radiogroup-extending-relativelayout/6320518#comment31569630_6320518


Setup
=====

1. Drop the source and values files into your project
2. Modify RelativeRadioGroup.java to include your generated R
3. Use RelativeRadioGroup in your layout files
