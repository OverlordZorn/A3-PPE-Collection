## Drunk

```
PP_wetD = ppEffectCreate ["WetDistortion",300];
PP_wetD ppEffectEnable true;
PP_wetD ppEffectAdjust [0.09,0.88,-1.15,1,1,1,1,0.02,0.02,0.02,0.02,0.1,0.1,0.2,0.2];
PP_wetD ppEffectCommit 0;
PP_dynamic = ppEffectCreate ["DynamicBlur",500];
PP_dynamic ppEffectEnable true;
PP_dynamic ppEffectAdjust [0.14];
PP_dynamic ppEffectCommit 0;
// Date YYYY-MM-DD-HH-MM: [2035,6,24,6,25]. Overcast: 0.3. Fog: 0.0886257. Fog params: [0.0800014,0.013,0] 
// GF PostProcess Editor parameters: Copy the following line to clipboard and click Import in the editor.
//[[false,100,[0.17,0.17,0.15,0.36]],[false,200,[0.05,0.05,true]],[true,300,[0.09,0.88,-1.15,1,1,1,1,0.02,0.02,0.02,0.02,0.1,0.1,0.2,0.2]],[false,1500,[1,1,0,[0,0,0,0],[0.64,5,4.77,2],[-0.83,2.13,-0.98,0],[0,0,0,0,0,0,4]]],[true,500,[0.14]],[false,2000,[0.2,1,1,0.5,0.5,true]],[false,2500,[1,1,1]]]
```

## Heavy Drunk

```
PP_radial = ppEffectCreate ["radialBlur",100];
PP_radial ppEffectEnable true;
PP_radial ppEffectAdjust [0.2,0.2,0.44,0.42];
PP_radial ppEffectCommit 0;
PP_chrom = ppEffectCreate ["ChromAberration",200];
PP_chrom ppEffectEnable true;
PP_chrom ppEffectAdjust [0.4,0.17,true];
PP_chrom ppEffectCommit 0;
PP_wetD = ppEffectCreate ["WetDistortion",300];
PP_wetD ppEffectEnable true;
PP_wetD ppEffectAdjust [0.09,0.88,-1.15,1,1,1,1,0.02,0.02,0.02,0.02,0.1,0.1,0.2,0.2];
PP_wetD ppEffectCommit 0;
PP_dynamic = ppEffectCreate ["DynamicBlur",500];
PP_dynamic ppEffectEnable true;
PP_dynamic ppEffectAdjust [0.14];
PP_dynamic ppEffectCommit 0;
// Date YYYY-MM-DD-HH-MM: [2035,6,24,6,25]. Overcast: 0.3. Fog: 0.0886257. Fog params: [0.0800014,0.013,0] 
// GF PostProcess Editor parameters: Copy the following line to clipboard and click Import in the editor.
//[[true,100,[0.2,0.2,0.44,0.42]],[true,200,[0.4,0.17,true]],[true,300,[0.09,0.88,-1.15,1,1,1,1,0.02,0.02,0.02,0.02,0.1,0.1,0.2,0.2]],[false,1500,[1,1,0,[0,0,0,0],[0.64,5,4.77,2],[-0.83,2.13,-0.98,0],[0,0,0,0,0,0,4]]],[true,500,[0.14]],[false,2000,[0.2,1,1,0.5,0.5,true]],[false,2500,[1,1,1]]]
```

## LSD
![alt text](107410_20220920032419_1.png)
```
PP_chrom = ppEffectCreate ["ChromAberration",200];
PP_chrom ppEffectEnable true;
PP_chrom ppEffectAdjust [0.05,0.05,true];
PP_chrom ppEffectCommit 0;
PP_colorC = ppEffectCreate ["ColorCorrections",1500];
PP_colorC ppEffectEnable true;
PP_colorC ppEffectAdjust [1,1,0,[0,0,0,0],[0.64,5,4.77,2],[-0.83,2.13,-0.98,0],[0,0,0,0,0,0,4]];
PP_colorC ppEffectCommit 0;
PP_dynamic = ppEffectCreate ["DynamicBlur",500];
PP_dynamic ppEffectEnable true;
PP_dynamic ppEffectAdjust [0.25];
PP_dynamic ppEffectCommit 0;
PP_film = ppEffectCreate ["FilmGrain",2000];
PP_film ppEffectEnable true;
PP_film ppEffectAdjust [0.45,0.71,1.46,0.32,0.5,true];
PP_film ppEffectCommit 0;
PP_colorI = ppEffectCreate ["ColorInversion",2500];
PP_colorI ppEffectEnable true;
PP_colorI ppEffectAdjust [0.39,0.42,0.41];
PP_colorI ppEffectCommit 0;
// Date YYYY-MM-DD-HH-MM: [2035,6,24,6,25]. Overcast: 0.3. Fog: 0.0886257. Fog params: [0.0800014,0.013,0] 
// GF PostProcess Editor parameters: Copy the following line to clipboard and click Import in the editor.
//[[false,100,[0.17,0.17,0.15,0.36]],[true,200,[0.05,0.05,true]],[false,300,[1,0.2,0.2,1,1,1,1,0.05,0.01,0.05,0.01,0.1,0.1,0.2,0.2]],[true,1500,[1,1,0,[0,0,0,0],[0.64,5,4.77,2],[-0.83,2.13,-0.98,0],[0,0,0,0,0,0,4]]],[true,500,[0.25]],[true,2000,[0.45,0.71,1.46,0.32,0.5,true]],[true,2500,[0.39,0.42,0.41]]]
```

## Hellscape
![alt text](107410_20240305050122_1.png)
```
PP_radial = ppEffectCreate ["radialBlur",100];
PP_radial ppEffectEnable true;
PP_radial ppEffectAdjust [0.01,0.15,0.22,0.24];
PP_radial ppEffectCommit 0;
PP_chrom = ppEffectCreate ["ChromAberration",200];
PP_chrom ppEffectEnable true;
PP_chrom ppEffectAdjust [0,0.36,true];
PP_chrom ppEffectCommit 0;
PP_wetD = ppEffectCreate ["WetDistortion",300];
PP_wetD ppEffectEnable true;
PP_wetD ppEffectAdjust [0.43,0.2,0.2,0.16,0.95,0.89,0.95,0.1,0.1,0.1,0.1,0,0,0,0];
PP_wetD ppEffectCommit 0;
PP_colorC = ppEffectCreate ["ColorCorrections",1500];
PP_colorC ppEffectEnable true;
PP_colorC ppEffectAdjust [1,1,0,[0,0,0,0],[1,0,0,-0.09],[0.33,0.33,0.47,-0.22],[0,0,0,0,0,0,4]];
PP_colorC ppEffectCommit 0;
PP_film = ppEffectCreate ["FilmGrain",2000];
PP_film ppEffectEnable true;
PP_film ppEffectAdjust [0.67,1.5,1.59,0.56,0.69,true];
PP_film ppEffectCommit 0;
// Date YYYY-MM-DD-HH-MM: [2035,6,24,8,0]. Overcast: 0.792282. Fog: 0.0251019. Fog params: [0.0251019,0.015,100] 
// GF PostProcess Editor parameters: Copy the following line to clipboard and click Import in the editor.
//[[true,100,[0.01,0.15,0.22,0.24]],[true,200,[0,0.36,true]],[true,300,[0.43,0.2,0.2,0.16,0.95,0.89,0.95,0.1,0.1,0.1,0.1,0,0,0,0]],[true,1500,[1,1,0,[0,0,0,0],[1,0,0,-0.09],[0.33,0.33,0.47,-0.22],[0,0,0,0,0,0,4]]],[false,500,[1]],[true,2000,[0.67,1.5,1.59,0.56,0.69,true]],[false,2500,[1,1,1]]]
```

