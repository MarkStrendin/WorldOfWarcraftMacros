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

## Click to revive
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

# Druid specific

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
