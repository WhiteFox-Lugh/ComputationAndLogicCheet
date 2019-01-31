**自然演繹の推論規則**

![Assumption](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%28H%3AP%5Cin%5CGamma%29%7D%7B%5CGamma%5Cvdash%20P%7D%7E%28Assumption%29)

![-\>I](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%2CH%3AP%5Cvdash%20Q%7E%7E%7E%7E%7EH%5Cnotin%20dom%28%5CGamma%29%7D%7B%5CGamma%5Cvdash%20P%5Crightarrow%20Q%7D%7E%28%5Crightarrow%20I%29)

![->E](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20P%5Crightarrow%20Q%7E%7E%7E%7E%7E%5CGamma%5Cvdash%20P%7D%7B%5CGamma%5Cvdash%20Q%7D%7E%28%5Crightarrow%20E%29)

![foarll I](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%2Cx%3AT%5Cvdash%20P%7E%7E%7E%7E%7E%28x%5Cnotin%20dom%28%5CGamma%29%29%7D%7B%5CGamma%5Cvdash%5Cforall%20x%3AT%2CP%5Bx%5D%7D%7E%28%5Cforall%20I%29)

![forall E](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20%5Cforall%20x%3AT%2C%20P%5Bx%5D%7E%7E%7E%7E%7E%5CGamma%5Cvdash%20M%3AT%7D%7B%5CGamma%5Cvdash%20P%5BM%5D%7D%7E%28%5Cforall%20E%29)

![=I](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7BM_1%5Cleftrightarrow%20M_2%7E%7E%7E%7E%7E%5CGamma%5Cvdash%20M_1%3AT%7E%7E%7E%7E%7E%5CGamma%5Cvdash%20M_2%3AT%7D%7B%5CGamma%5Cvdash%20M_1%3DM_2%7D%7E%28%3DI%29)

![=E](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20M_1%3DM_2%7E%7E%7E%7E%7E%5CGamma%5Cvdash%20P%5BM_1%5D%7D%7B%5CGamma%5Cvdash%20P%5BM_2%5D%7D%7E%28%3DE%29)

![InjS](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20S%28M_1%29%3DS%28M_2%29%7D%7B%5CGamma%5Cvdash%20M_1%3DM_2%7D%7E%28InjS%29)

![ContraNat](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20O%3DS%28M%29%7E%7E%7E%7E%7E%5CGamma%5Cvdash%20P%3Aprop%7D%7B%5CGamma%5Cvdash%20P%7D%7E%28ContraNat%29)

![IndNat](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20P%5BO%5D%7E%7E%7E%7E%7E%5CGamma%2C%7Ey%3Anat%2C%7EH%3AP%5By%5D%5Cvdash%20P%5BS%28y%29%5D%7D%7B%5CGamma%5Cvdash%5Cforall%20x%3Anat%2CP%5Bx%5D%7D%7E%28IndNat%29)

![ContraBool](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20true%3Dfalse%7E%7E%7E%7E%7E%5CGamma%5Cvdash%20P%3Aprop%7D%7B%5CGamma%5Cvdash%20P%7D%7E%28ContraBool%29)

![IndBool](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20P%5Btrue%5D%7E%7E%7E%7E%7E%5CGamma%5Cvdash%20P%5Bfalse%5D%7D%7B%5CGamma%5Cvdash%5Cforall%20x%3Abool%2CP%5Bx%5D%7D%7E%28IndBool%29)

![And-I](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20P%7E%7E%7E%7E%7E%5CGamma%5Cvdash%20Q%7D%7B%5CGamma%5Cvdash%20P%5Cwedge%20Q%7D%7E%28%5Cwedge-I%29)

![And-E1](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20P%5Cwedge%20Q%7D%7B%5CGamma%5Cvdash%20P%7D%7E%28%5Cwedge-E1%29)

![And-E2](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20P%5Cwedge%20Q%7D%7B%5CGamma%5Cvdash%20Q%7D%7E%28%5Cwedge-E2%29)

![And-E3](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20P%5Cwedge%20Q%7E%7E%7E%7E%5CGamma%2CH_1%3AP%2CH2%3AQ%5Cvdash%20R%7E%7E%28H_1%5Cne%20H_2%7Eand%7EH_1%2CH_2%5Cnotin%20dom%28%5CGamma%29%29%7D%7B%5CGamma%5Cvdash%20R%7D%7E%28%5Cwedge-E3%29)

![Or-I1](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20P%7E%7E%7E%5CGamma%5Cvdash%20Q%3Aprop%7D%7B%5CGamma%5Cvdash%20P%5Cvee%20Q%7D%7E%28%5Cvee-I1%29)

![Or-I2](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20P%3Aprop%7E%7E%7E%5CGamma%5Cvdash%20Q%7D%7B%5CGamma%5Cvdash%20P%5Cvee%20Q%7D%7E%28%5Cvee-I2%29)

![Or-E](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20P%5Cvee%20Q%7E%7E%7E%5CGamma%2CH_1%3AP%5Cvdash%20R%7E%7E%7E%5CGamma%2CH_2%3AQ%5Cvdash%20R%7E%7E%28H_1%2CH_2%5Cnotin%20dom%28%5CGamma%29%29%7D%7B%5CGamma%5Cvdash%20R%7D%7E%28%5Cvee-E%29)

![bottom-E](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%5Cperp%7E%7E%7E%5CGamma%5Cvdash%20P%3Aprop%7D%7B%5CGamma%5Cvdash%20P%7D%7E%28%5Cperp-E%29)

![exists-I](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%20M%3AT%7E%7E%7E%7E%5CGamma%5Cvdash%20P%5BM%5D%7D%7B%5CGamma%5Cvdash%5Cexists%20x%3AT%2C%20P%5Bx%5D%7D%7E%28%5Cexists%20I%29)

![exists-E](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%5Cvdash%5Cexists%20x%3AT%2CP%5Bx%5D%7E%7E%7E%7E%5CGamma%2Cx%3AT%2CH%3AP%5Bx%5D%5Cvdash%20Q%7E%7E%7E%5CGamma%5Cvdash%20Q%3Aprop%7E%7E%28x%5Cne%20H%20%7Eand%7Ex%2CH%5Cnotin%20dom%28%5CGamma%29%29%7D%7B%5CGamma%5Cvdash%20Q%7D%7E%28%5Cexists-E%29)

![exists-P](https://latex.codecogs.com/svg.latex?%5Cinline%20%5Cfrac%7B%5CGamma%2Cx%3AT%5Cvdash%20P%3Aprop%7D%7B%5CGamma%5Cvdash%5Cexists%20x%3AT%2C%20P%3Aprop%7D%7E%28%5Cexists%20P%29)


