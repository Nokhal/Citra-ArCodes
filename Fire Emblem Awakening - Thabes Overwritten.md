# Fire Emblem Awakening - Thabes

## Setup
Citra/Mandarine Action Replay codes working for the following setup : 

Fire Emblem Awakening US  *00040000000A0500*

[Thabes Overwritten](https://gamebanana.com/mods/555858) v0.1.2              
[UGA](https://gamebanana.com/mods/424187) v8.5.1 installed following the exact instruction in Thabes Overwritten above     

## Troubleshooting
### No code works
You have most likely the wrong game version. Only the US version is supported.

### Shader/XP/Move Twice code works but not gold/renown/items 
Make sure only those two mods are installed (Uninstall USV if necessary, reinstall it later once you have cheated enough)      
             
If despite this code are still broken, an update to Thabes or UGA might have broken the offsets.            
Please create an issue [here](https://github.com/Nokhal/Citra-ArCodes/issues) to report the problem. Or do a PR if you also fixed it.

## Cheats
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
    D3000000 15367692
    100002CA 00000063
    
    [Second Seal x99]
    D3000000 15367692
    100002CC 00000063
    
    [Arms Scroll x 99]
    D3000000 15367692
    100002C8 00000063
    
    [Boots x 99]
    D3000000 15367692
    100002C6 00000063
    
    [Seed of Trust x 99]
    D3000000 15367692
    100002DC 00000063
    
    [Iote's Shield x 99]
    D3000000 15367692
    100002E8 00000063
    
    [Limit Breaker x 99]
    D3000000 15367692
    100002EA 00000063
    
    [Dread Scroll x99]
    D3000000 15367692
    100002EE 00000063
    
    [Wedding Bouquet x 99]
    D3000000 15367692
    100002F0 00000063
    
    [Thrift Scroll x 99]
    D3000000 15367692
    1000038E 00000063
    
    [Gale Scroll x 99]
    D3000000 15367692
    10000390 00000063
    
    [Counter Scroll x 99]
    D3000000 15367692
    10000392 00000063
    
    [Gamble Scroll x 99]
    D3000000 15367692
    10000394 00000063
    
    [Pavise Scroll x 99]
    D3000000 15367692
    10000396 00000063
    
    [Renewal Scroll x 99]
    D3000000 15367692
    10000398 00000063
    
    [Miracle Scroll x 99]
    D3000000 15367692
    1000039A 00000063
    
    [Wrath Scroll x 99]
    D3000000 15367692
    1000039C 00000063
    
    [Vantage Scroll x 99]
    D3000000 15367692
    1000039E 00000063



