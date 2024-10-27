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