# PidgeonsRP

/give @n minecraft:iron_sword[minecraft:item_model="pidgeons:letter_knife",minecraft:item_name="Letter Knife"]

/give Captain_Tenne minecraft:music_disc_11[!minecraft:jukebox_playable,minecraft:item_name="Stamp",minecraft:rarity=epic,minecraft:item_model="pidgeons:stamp",lore=[{text:"Seal:",color:"gray",italic:false},{italic:false,color:"white",text:" Thareka Zegel"}]]

/give Captain_Tenne minecraft:music_disc_11[!minecraft:jukebox_playable,minecraft:item_name="Stamp",minecraft:rarity=common,minecraft:item_model="pidgeons:stamp"]

/give Captain_Tenne minecraft:music_disc_11[!minecraft:jukebox_playable,minecraft:item_name="Pidgeon",minecraft:custom_data={pidgeon:true},minecraft:item_model="pidgeons:pidgeon",minecraft:consumable={consume_seconds:10000000}]

/give Captain_Tenne book[minecraft:item_model="pidgeons:sealed_scroll",minecraft:item_name="Sealed Scroll",minecraft:custom_data={sealed:scroll},minecraft:max_stack_size=1,minecraft:consumable={consume_seconds:1,animation:crossbow,sound:item.brush.brushing.generic,has_consume_particles:false},minecraft:enchantment_glint_override=true]

/give Captain_Tenne book[minecraft:item_model="pidgeons:sealed_book",minecraft:item_name="Sealed Book",minecraft:custom_data={sealed:book},minecraft:max_stack_size=1,minecraft:consumable={consume_seconds:1,animation:crossbow,has_consume_particles:false,sound:item.brush.brushing.generic},minecraft:enchantment_glint_override=true]

/give Captain_Tenne book[minecraft:item_model="pidgeons:sealed_scroll",minecraft:item_name="Sealed Scroll",minecraft:custom_data={sealed:scroll},minecraft:max_stack_size=1,minecraft:consumable={consume_seconds:1,animation:crossbow,sound:item.brush.brushing.generic,has_consume_particles:false},minecraft:enchantment_glint_override=true,minecraft:lore=[{italic:false,color:"gray",text:"Seal:"},{color:"dark_green",italic:false,text:" Deltar zegel"}]]

/give Captain_Tenne minecraft:written_book[minecraft:lore=[{italic:false,text:"Broken Seal:",color: "gray"},{italic:false,text:" Deltar zegel",color:"yellow"}],minecraft:written_book_content={pages:[{raw:"Test"}],title:{raw:"Something"},resolved:true}]

# Pidgeon model spawn egg
/give Captain_Tenne minecraft:chicken_spawn_egg[rarity=uncommon,item_name="Pidgeon",item_model="pidgeons:pidgeon",entity_data={id:"minecraft:item_display",item:{id:"minecraft:stone",components:{item_model:"pidgeons:pidgeon_nest"}}}]

# Display based pidgeons
/give Captain_Tenne minecraft:chicken_spawn_egg[rarity=uncommon,item_name="Pidgeon",item_model="pidgeons:pidgeon",entity_data={item:{id:"minecraft:stone",components:{item_model:"pidgeons:pidgeon_sitting"}},id:"minecraft:item_display",Tags:["new_pidgeon"],shadow_radius:0.325}]
