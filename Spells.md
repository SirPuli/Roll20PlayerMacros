# Spells

####List all spells
&{template:default}{{name=@{selected|character_name} Spellcasting
}}{{ Spell DC @{selected|spell_save_dc} = @{selected|spell_attack_bonus} to hit with spell attacks
}}{{ Cantrips = [@{selected|repeating_spell-cantrip_$0_spellname}](~selected|repeating_spell-cantrip_$0_spell)
}}{{ 1st (SLOTS) = [@{selected|repeating_spell-1_$0_spellname}](~selected|repeating_spell-1_$0_spell)
}}{{ 2nd (SLOTS) = [@{selected|repeating_spell-2_$0_spellname}](~selected|repeating_spell-2_$0_spell)
}}{{ 3rd (SLOTS) = [@{selected|repeating_spell-3_$0_spellname}](~selected|repeating_spell-3_$0_spell)
}}

#### Mirror Image
&{template:default}{{name=Mirror Image}}?{Number of Images|Three, Six|Two, Eight|One, Eleven}{{?{Number of Images} or more, the attack hits the Image:=[[1d20]]}}{{Mirror Image AC:=[[10+@{dexterity_mod}]]}}
