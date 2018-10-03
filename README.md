# Baby_CNN

### Version 0  EchoBaby 2D Unet Experiment

MASKS_DN = 'GM_0.5'
sz = 256
bs = 32
nw = 16

val_idxs = list(range(200))
lr=4e-2
wd=1e-7

lrs = np.array([lr/100,lr/10,lr])
learn.fit(lrs,1,wds=wd,cycle_len=8,use_clr=(5,8))


epoch      trn_loss   val_loss   <lambda>   dice           
    0      0.124921   0.070693   0.953168   0.480944  
    1      0.08551    0.068323   0.959493   0.541697        
    2      0.077828   0.055344   0.975561   0.773406        
    3      0.071883   0.059602   0.965945   0.692962        
    4      0.066565   0.058398   0.968557   0.715761        
    5      0.062338   0.053722   0.972558   0.756356        
    6      0.060016   0.059834   0.968537   0.707804        
    7      0.058215   0.059893   0.970572   0.728703       
  
  









