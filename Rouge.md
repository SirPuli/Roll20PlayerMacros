# Rouge

#### Sneak Attack Single/1st Class - If you are multi classing and rouge is not your 1st class use the multi class macro
&{template:default}?{Crit?|No, [[ceil(@{base_level}/2)]]|Yes, [[[[ceil(@{base_level}/2)]]*2]]}{{name=Sneak Attack}}{{Extra damage:=[[?{Crit?}d6]]}}

#### Sneak Attack Multi Class - If you are multiclassing more then 2 class and rouge isn't your 2nd class, replace the number in *multiclass1_lvl* with the appropriate number
&{template:default}?{Crit?|No, [[ceil(@{multiclass1_lvl}/2)]]|Yes, [[[[ceil(@{multiclass1_lvl}/2)]]*2]]}{{name=Sneak Attack}}{{Extra damage:=[[?{Crit?}d6]]}}
