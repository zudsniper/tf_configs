## `zod` `tf2` `configs`  
> _yes they are weird_   
> _no i will not explain_   
> _no, i also **cant explain**_    
  
<div align="center">

![zod.tf logo](https://i.imgur.com/cw3A8u0.gif)   

</div>  

## SUMMARY

TF2 custom configuration files which set graphic & functional configurations for the _peculiar_ way that I specifically like to play this game.  

---

### TOOLS & CONFIGS

**GENERAL/PERFORMANCE**    
I also use [mastercomfig](https://mastercomfig.com) as it is excellent. Essentially if you are still playing this game, and you're _not_ using mastercomfig... how does your game even work? 
Thank you very much [`@mcoms`](https://github.com/mcoms) for the extensive work you do that makes the experiences of normal players much, much, much easier. 

**HUD**  
For huds I use the [TF2 Hud Editor](https://criticalflaw.ca/TF2HUD.Editor/) by [`@criticalflaw`](https://github.com/criticalflaw) -- the creator of a ton of everyone's favorite huds as well as just a very helpful member of the community. I haven't met you sir, but I would love to, and I hope you're doing well. Your huds and now this excellent tool are very useful. Thank you! 

### LAUNCH OPTIONS

Here are my launch options, do with them as you will.[^2] 

```
-w 2560 -h 1440 -noborder -windowed -novid -nojoy -nosteamcontroller -nohltv -particles 1 -precachefontchars -noquicktime
```

### PRELOADING  

> `DISCLAIMER`   
> This is ***NOT*** supported, endorsed, or tolerated by Valve Software, and I do ***NOT*** endorse its use.  
  
So if you still want to preload so that you can use your custom models or whatever `.vpk`s you've got that don't make it past `sv_pure`, you've got to find a copy of `preload_room.bsp`, which I unfortunately do not have for you as I do not use this. However, if you look, you might be able to find it somewhere online.  

After obtaining this map & placing it into your `tf/maps` folder, you can use these two lines _(from my autoexec)_ to preload. They must be placed into your `autoexec.cfg` script, preferably as close to the top as possible.   
<sup>NOTE: Hitsound/Killsound/Audio preloads in general are... finicky. YMMV.</sup>  

```js
// BYPASS SV_PURE
sv_allow_point_servercommand always
map_background preload_room
``` 

---

> ### By [@zudsniper](https://gh.zod.tf)  
> #### Rewritten[^1] `05/22/2023` with help from [@rc4](https://github.com/rc4)  

---


[^1]: ... I wiped my PC and remembered preeetttyyy much everything else  
[^2]: These are **mostly** the instructed launch options from @mastercomfig. No wait, it IS _literally_ just those.   
