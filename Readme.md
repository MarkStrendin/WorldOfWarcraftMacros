# Mark's World of Warcraft Macros
Just putting these here so that they are easy to share and recover.


# Healing

## Hover Healing
~~~
#showtooltip
/use [@mouseover,help,nodead][help,nodead][@player] Lifebloom
~~~

## Click to Innervate
~~~
#showtooltip
/cast [@none] Innervate
~~~

## Click to Rebirth
~~~
#showtooltip
/cast [@none] Rebirth
~~~

# Tanking

## Click to provoke
~~~
#showtooltip
/cast [@none] Growl
~~~

Allows you to Growl without deselecting your current target - for adds, etc.
Replace "Growl" with whatever provoke ability you have.

# Druid specific

## Druid sprint
~~~
#showtooltip
/castsequence reset=120 Stampeding Roar, Dash
~~~

## Druid sprint (For Worgens)
~~~
#showtooltip
/castsequence reset=120 Stampeding Roar, Darkflight, Dash
~~~
If you shift+click Darkgflight, it puts *Darkflight(Racial)*, which will not work - you must remove "(Racial)".
Darkflight isn't as fast as dash, but it also doesn't auto-shift you to cat form.

## Wild Charge
This macro prompts you to click someone (to fly to) if you are in caster form, and just casts Wild Charge if you are in bear or cat form.
~~~
#showtooltip
/cast [form:1/2] Wild Charge ; [@none] Wild Charge
~~~

## Growl if in bear form, transform into bear form if not
~~~
#showtooltip
/cast [form:1] Growl ; Bear Form(Shapeshift)
~~~

## Click to Regrowth
For free cat form regrowths from Predatory Swiftness. Allows you to cast without deselecting your current target.
~~~
#showtooltip
/cast [@none] Growl
~~~

# General

## Exit Vehicle
~~~
/script VehicleExit();
~~~

## Click Yes/OK on a dialog box
Or more specifically, whatever the first button in the dialog is
~~~
/click StaticPopup1Button1
~~~
