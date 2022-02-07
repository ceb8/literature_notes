
# Radio Emission sources
&nbsp;

&nbsp;

## 3D MHD simulations and synthetic radio emission from an oblique rotating magnetic massive star 
###  Daley-Yates, S. ; Stevens, I. R. ; ud-Doula, A.
[ADS](https://ui.adsabs.harvard.edu/abs/2019MNRAS.489.3251D/abstract) ~ 
[OneDrive](https://universityofstandrews907-my.sharepoint.com/:b:/r/personal/cb432_st-andrews_ac_uk/Documents/Prominance%20Papers/stz1982.pdf?csf=1&web=1&e=gn0Wx1)
~ `\cite{DaleyYates_2019MNRAS.489.3251D}`

This paper has equations for getting radio intensity given a known stellar atmosphere. 
Thee real explanation is in an earlier (2016) paper also by Simon et al.


&nbsp;

## :boom: Submillimetre free-free emission from the winds of massive stars in the age of Atacama Large Millimeter/submillimeter Array  
### Daley-Yates, S.; Stevens, I. R.; Crossland, T. D.  

[ADS](https://ui.adsabs.harvard.edu/abs/2016MNRAS.463.2735D/abstract) 
 ~ 
[OneDrive](https://universityofstandrews907-my.sharepoint.com/:b:/r/personal/cb432_st-andrews_ac_uk/Documents/Prominance%20Papers/stw2184.pdf?csf=1&web=1&e=XFFItH)
~ `\cite{DaleyYates_2016MNRAS.463.2735D}` ~ :page_facing_up:
 
**Calculating flux from stellar wind**
- In this paper, Simon takes the stellar wind model developed by [Wright and Barlow](The-radio-and-infrared-spectrum-of-early-type-stars-undergoing-mass-loss) and relaxes soe of the constraints on it, which he can do because of his numerical approach.
- The ultimate goal in this paper is to create synthetic radio emission for accelerating stellar winds. 
- While the numerical approach allows for the strict assumptions in Wright and Barlow to be relaxed, a wind density profile must be specified (this is something we can get around by knowing the magnetic field and therefore the density everywhere)
- This paper goes through the math and simplifies the integrals in ways that we cannot, because they make certain assumptions, basically we have to leave everything inside the integrand because we don't assume isothermal (see notes on printed out copy for details)
- In the radio regime <img src="https://render.githubusercontent.com/render/math?math=h \nu \ll k_BT"> so the Raleigh-Jeans approximation applies, which allows for the simplification of both the planck function (*B<sub>ν</sub>*) and the absorption constant (κ) (eq. 10)
- Simon brings this all together to get the total flux from the wind, for our purposes we won't do that final integral since we want an 2D image not a single total value

**Defining an characteristic radius for the coronal radio photosphere**
- Discusses a "characteristic" radius (*R<sub>ν</sub>*) where for all radii greating than *R<sub>ν</sub>* the wind is optically thin.
- Different sources define this differently, can basically choose whatever optical depth you want. Simon works it out for  <img src="https://render.githubusercontent.com/render/math?math=\tau=1">


&nbsp;

## The radio and infrared spectrum of early type stars undergoing mass loss 
###  Wright, A. E. ; Barlow, M. J. 
[ADS](https://ui.adsabs.harvard.edu/abs/1975MNRAS.170...41W/abstract) ~ `\cite{Wright_1975MNRAS.170...41W}`

**The notes from this paper are primarily in my research notebook pg 12-13.**

It assumes constant speed wind and goes through the calculations for optical depth and line of sight intensity. The constant wind speed is only used for getting the atmosphere density, so if we have another way to get that (i.e. surface magnetic field maps) then we don't have to make that assumption. This also describes the gaunt factor, although it leaves the derivation of the free-free absorption constant for textbooks (see next entry).


&nbsp;

## :closed_book: Stellar Atmospheres
### Mihalas
`\cite{Mihalas_1978stat.book.....M}` ~ QB 809.M55F78

#### On the derivation of the free-free absorption coefficient
- In strict thermodynamic equilibrium (TE) the radiation field is isotropic and <img src="https://render.githubusercontent.com/render/math?math=I_{\nu} \equiv B_{\nu}">  
  This holds for local thermodynamic equilibrium too (LTE) and is something we assume throughout
- In TE, each upward (atomic energy) transision in range <img src="https://render.githubusercontent.com/render/math?math=(\nu,\nu + d\nu)"> must be balenced by emission in the same range
- "quantum defect method" for deriving <img src="https://render.githubusercontent.com/render/math?math=\kappa_{\nu}"> (free-free absorption coefficient)
- Looking at the free-free opacity of H  
So assuming fully ionized 100% hydrogen atmosphere
- A free electrion passing near a proton causes a transitory dipole moment and absorptions and emissions of photons (with consequent change en election's *E*) become possible
- Derived free-free absortion constant for fully ionized hydrogen atmosphere:  
<img src="https://render.githubusercontent.com/render/math?math=\kappa_{\nu,ff} = 3.6(10^8) g_{III}(\nu,T)\nu^{-3}T^{-1/2}n_en_p(1-e^\frac{-h\nu}{kT})"> where <img src="https://render.githubusercontent.com/render/math?math=g_{III}"> is the gaunt factor, which is given in [Wright and Barlow, 1975](The-radio-and-infrared-spectrum-of-early-type-stars-undergoing-mass-loss).

&nbsp;

## :boom: Simplified expressions for the gyrosynchrotron radiation from mildly relativistic, nonthermal and thermal electrons 
### Dulk, G. A. ; Marsh, K. A. 
[ADS](https://ui.adsabs.harvard.edu/abs/1982ApJ...259..350D/abstract)
~ [OneDrive](https://universityofstandrews907-my.sharepoint.com/:b:/r/personal/cb432_st-andrews_ac_uk/Documents/Prominance%20Papers/1982ApJ___259__350D.pdf?csf=1&web=1&e=5fCRmf)
~ `\cite{Dulk_1982ApJ...259..350D}`


&nbsp;

## :boom: Radio emission from the sun and stars
### Dulk, G. A. 
[ADS](https://ui.adsabs.harvard.edu/abs/1985ARA%26A..23..169D/abstract)
~ [OneDrive](https://universityofstandrews907-my.sharepoint.com/:b:/r/personal/cb432_st-andrews_ac_uk/Documents/Prominance%20Papers/1985ARA+A__23__169D.pdf?csf=1&web=1&e=Glp9qJ)
~
`\cite{Dulk_1985ARA&A..23..169D}`

&nbsp;

## :boom: Directivity of the Radio Emission from the K1 Dwarf Star AB Doradus 
###  Lim, Jeremy ; White, Stephen M. ; Nelson, Graam J. ; Benz, Arnold O. 
[ADS](https://ui.adsabs.harvard.edu/abs/1994ApJ...430..332L/abstract) ~ 
[OneDrive](https://universityofstandrews907-my.sharepoint.com/:b:/r/personal/cb432_st-andrews_ac_uk/Documents/Prominance%20Papers/1994ApJ___430__332L.pdf?csf=1&web=1&e=9lb6ag)
~ `\cite{Lim_1994ApJ...430..332L}`

&nbsp;

## :boom: Thermal radio emission from early-type binary systems 
### Stevens, Ian R. 
[ADS](https://ui.adsabs.harvard.edu/abs/1995MNRAS.277..163S/abstract) ~ 
[OnceDrive](https://universityofstandrews907-my.sharepoint.com/:b:/r/personal/cb432_st-andrews_ac_uk/Documents/Prominance%20Papers/mnras277-0163.pdf?csf=1&web=1&e=MMz0b9)
~ `Stevens_1995MNRAS.277..163S`

&nbsp;




 
