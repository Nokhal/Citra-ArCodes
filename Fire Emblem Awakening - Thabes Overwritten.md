# Fire Emblem Awakening - Thabes

## Setup
Citra/Mandarine Action Replay codes working for the following setup : 

Fire Emblem Awakening US  *00040000000A0500*

All dlcs (install them trough a CIA file for example)

[Thabes Overwritten](https://gamebanana.com/mods/555858) v0.1.2              
[UGA](https://gamebanana.com/mods/424187) v8.5.1 installed following the exact instruction in Thabes Overwritten above.             
         
Nonetheless, most of those code should work for vanilla awakening.

## Troubleshooting
### No code works
You have most likely the wrong game version. Only the US version is supported, all DLC installed, and no online content.

### Shader/XP/Move Twice code works but not gold/renown/items 
This is very strange, as i'm using pointers to pop the items. In fact, outside of Thabes exlusive items, the item code should work in vanilla awakening. 
Make sure only the two above mods are installed (Uninstall USV if necessary, reinstall it later once you have cheated enough)      
             
If despite this code are still broken, an update to Thabes or UGA might have broken the offsets.            
Please create an issue [here](https://github.com/Nokhal/Citra-ArCodes/issues) to report the problem. Or do a PR if you also fixed it.

## Cheats
You'll notice the item offset is equal to it's hex Item id * 2, so if any item you want is missing feel free to craft your own codes.           
You can copy paste the content below directly in your *cheat/00040000000A0500.txt* file


     
    [IMPORTANT Shader fix]
    *mandarine_enabled
    *fix freezes in battle animations
    001ecd54 E3A01002
    
    [xp 100 per action]
    00277A5C E3510001
        
    [Perfect Growth]
    D3000000 00000000
    002CF024 E3A00000
    
    [Infinite Moves]
    00177CB4 E1A00000
    
    [Enemy Drop Items]
    *most items can only be used in the map you dropped them
    *sell them for 0 afterward
    00199848 E1D11AB2
    0019984C E3510000
    
    [Max Gold]
    D3000000 14000000
    009B2A70 000F423F
    
    [Max Renown]
    D3000000 14000000
    009B2A74 0001869F
    
    [Master Seal x99]
    604D0C7C 00000000
    B04D0C7C 00000000
    10000164 00000063
    
    [Second Seal x99]
    604D0C7C 00000000
    B04D0C7C 00000000
    10000166 00000063
    
    [Arms Scroll x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    10000162 00000063
    
    [Boots x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    10000160 00000063
    
    [Seed of Trust x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    10000176 00000063
    
    [Iote's Shield x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    10000182 00000063
    
    [Limit Breaker x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    10000184 00000063
    
    [Dread Scroll x99]
    604D0C7C 00000000
    B04D0C7C 00000000
    10000188 00000063
    
    [Wedding Bouquet x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    1000018A 00000063
    
    [Thrift Scroll x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    10000228 00000063
    
    [Gale Scroll x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    1000022A 00000063
    
    [Counter Scroll x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    1000022C 00000063
    
    [Gamble Scroll x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    1000022E 00000063
    
    [Pavise Scroll x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    10000230 00000063
    
    [Renewal Scroll x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    10000232 00000063
    
    [Miracle Scroll x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    10000234 00000063
    
    [Wrath Scroll x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    10000236 00000063
    
    [Vantage Scroll x 99]
    604D0C7C 00000000
    B04D0C7C 00000000
    10000238 00000063



