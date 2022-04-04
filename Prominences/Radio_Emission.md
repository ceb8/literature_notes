
# Radio Emission sources
&nbsp;

&nbsp;

## 3D MHD simulations and synthetic radio emission from an oblique rotating magnetic massive star 
###  Daley-Yates, S. ; Stevens, I. R. ; ud-Doula, A.
[ADS](https://ui.adsabs.harvard.edu/abs/2019MNRAS.489.3251D/abstract) ~ 
[OneDrive](https://universityofstandrews907-my.sharepoint.com/:b:/r/personal/cb432_st-andrews_ac_uk/Documents/Prominance%20Papers/stz1982.pdf?csf=1&web=1&e=gn0Wx1)
~ `\cite{DaleyYates_2019MNRAS.489.3251D}` ~ :page_facing_up:

This paper has equations for getting radio intensity given a known stellar atmosphere. 
The real explanation is in an earlier (2016) paper also by Simon et al.


&nbsp;

## Submillimetre free-free emission from the winds of massive stars in the age of Atacama Large Millimeter/submillimeter Array  
### Daley-Yates, S.; Stevens, I. R.; Crossland, T. D.  

[ADS](https://ui.adsabs.harvard.edu/abs/2016MNRAS.463.2735D/abstract) 
 ~ 
[OneDrive](https://universityofstandrews907-my.sharepoint.com/:b:/r/personal/cb432_st-andrews_ac_uk/Documents/Prominance%20Papers/stw2184.pdf?csf=1&web=1&e=XFFItH)
~ `\cite{DaleyYates_2016MNRAS.463.2735D}` ~ :page_facing_up:
 
**Calculating flux from stellar wind**
- In this paper, Simon takes the stellar wind model developed by [Wright and Barlow](The-radio-and-infrared-spectrum-of-early-type-stars-undergoing-mass-loss) and relaxes some of the constraints on it, which he can do because of his numerical approach.
- The ultimate goal in this paper is to create synthetic radio emission for accelerating stellar winds. 
- While the numerical approach allows for the strict assumptions in Wright and Barlow to be relaxed, a wind density profile must be specified (this is something we can get around by knowing the magnetic field and therefore the density everywhere)
- This paper goes through the math and simplifies the integrals in ways that we cannot, because they make certain assumptions, basically we have to leave everything inside the integrand because we don't assume isothermal (see notes on printed out copy for details)
- In the radio regime <img src="https://render.githubusercontent.com/render/math?math=h \nu \ll k_BT"> so the Raleigh-Jeans approximation applies, which allows for the simplification of both the planck function (*B<sub>ν</sub>*) and the absorption constant (κ) (eq. 10)
- Simon brings this all together to get the total flux from the wind, for our purposes we won't do that final integral since we want an 2D image not a single total value

**Defining an characteristic radius for the coronal radio photosphere**
- Discusses a "characteristic" radius (*R<sub>ν</sub>*) where for all radii greating than *R<sub>ν</sub>* the wind is optically thin.
- Different sources define this differently, can basically choose whatever optical depth you want. Simon works it out for  <img src="https://render.githubusercontent.com/render/math?math=\tau=1">
- "At this frequency, for models with lower mass-loss rates, a terminal velocity wind may lead to a characteristic radius smaller then the stellar radius."  
Because of this Simon adds *R<sub>\*</sub>* to the original *R<sub>ν</sub>*, so it trends to *R<sub>\*</sub>* rather than 0


&nbsp;

## The radio and infrared spectrum of early type stars undergoing mass loss 
###  Wright, A. E. ; Barlow, M. J. 
[ADS](https://ui.adsabs.harvard.edu/abs/1975MNRAS.170...41W/abstract) ~ 
[OneDrive](https://universityofstandrews907-my.sharepoint.com/:b:/r/personal/cb432_st-andrews_ac_uk/Documents/Prominance%20Papers/1975MNRAS_170___41W.pdf?csf=1&web=1&e=ShXbP4)
~ `\cite{Wright_1975MNRAS.170...41W}`

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

## Simplified expressions for the gyrosynchrotron radiation from mildly relativistic, nonthermal and thermal electrons 
### Dulk, G. A. ; Marsh, K. A. 
[ADS](https://ui.adsabs.harvard.edu/abs/1982ApJ...259..350D/abstract)
~ [OneDrive](https://universityofstandrews907-my.sharepoint.com/:b:/r/personal/cb432_st-andrews_ac_uk/Documents/Prominance%20Papers/1982ApJ___259__350D.pdf)
~ `\cite{Dulk_1982ApJ...259..350D}`

Theoretical paper giving the following:
- Simplified expressions for gyrosynchrotron radiation from mildly relativistic electrons (both nonthermal and thermal)
- Covers 10keV to 1MeV electrons
 
&nbsp;

## Radio emission from the sun and stars
### Dulk, G. A. 
[ADS](https://ui.adsabs.harvard.edu/abs/1985ARA%26A..23..169D/abstract)
~ [OneDrive](https://universityofstandrews907-my.sharepoint.com/:b:/r/personal/cb432_st-andrews_ac_uk/Documents/Prominance%20Papers/1985ARA+A__23__169D.pdf?csf=1&web=1&e=Glp9qJ)
~
`\cite{Dulk_1985ARA&A..23..169D}`
 
 This is a theoretical paper that presents some simplifications of the equations for thermal and non-thermal electron radiation in the radio regime. 
 Underpins the equations used in Simon's papers.

&nbsp;

## Directivity of the Radio Emission from the K1 Dwarf Star AB Doradus 
###  Lim, Jeremy ; White, Stephen M. ; Nelson, Graam J. ; Benz, Arnold O. 
[ADS](https://ui.adsabs.harvard.edu/abs/1994ApJ...430..332L/abstract) ~ 
[OneDrive](https://universityofstandrews907-my.sharepoint.com/:b:/r/personal/cb432_st-andrews_ac_uk/Documents/Prominance%20Papers/1994ApJ___430__332L.pdf?csf=1&web=1&e=9lb6ag)
~ `\cite{Lim_1994ApJ...430..332L}`
 
**Main point**  
 - Presents models that can explain the observed radio emmission from AB Dor.  
 - Presents indirect evidence that active stars can have highly directional radio emission.
 - Presents evidence that the brightness temp of the radio emissions may be muich higher than previously thought.
 
 **Observations**
 - Light curves
 - Phase fold, radio peaks coincident with starspots
 
 **Results**
 - Very high brightness temp inferred for AB Dor suggest solar analogy for flares (that all stellar flares are just scaled up solar flares) may not always be true.
 - Emission shows two peaks in frequency
 - No circular polarization
 - 4 models to explain modulated emission:  
   1. Purely geometrical effects. Confines souces to small range of latitudes and dimensions. High brightness temp inferred (10^13 K)  
   2. Limb darkening added to number one. Doesn't change the parameters significantly.  
   3. Directivity outside of the source, i.e. vertical coronal structures around a starspot that absorb radiation along most but not all lines of sight. Limits the dimensions even more. Problem: to get teh observed frequencies the magnetic field over starspots must be very low (~10 G)  
   4. Directivity intrinsic to source (synchrotron emission). Required same dimensions as #3. Brightness temp can be lower but still up to 6x10^10 K. Problem: requires magnetic structures with weird shapes.


&nbsp;

## Thermal radio emission from early-type binary systems 
### Stevens, Ian R. 
[ADS](https://ui.adsabs.harvard.edu/abs/1995MNRAS.277..163S/abstract) ~ 
[OneDrive](https://universityofstandrews907-my.sharepoint.com/:b:/r/personal/cb432_st-andrews_ac_uk/Documents/Prominance%20Papers/mnras277-0163.pdf)
~ `\cite{Stevens_1995MNRAS.277..163S}`

- They are looking into the difference being in a binary system makes on thermal radio emission from early type stars
- They conclude it makes a lot of difference, and that the presence of a companion with a substantial wind will increase the expected thermal radio emission as compared to a single star with the same characteristics
- The degree to which the emission is altered is sensitive to the wind characteristics of the companion, and hot gas created by the wind collision plays a large roll
- This means that not taking binarity into account will cause an **overestimate of mass loss** from the componants in such systems
- In light of this they discuss methods to more accurately estimate mass loss for early type stars in binary systems

&nbsp;

## The Radio Activity-Rotation Relation of Ultracool Dwarfs
###  McLean, M. ; Berger, E. ; Reiners, A. 
[ADS](https://ui.adsabs.harvard.edu/abs/2012ApJ...746...23M/abstract) ~
[OneDrive](https://universityofstandrews907-my.sharepoint.com/personal/cb432_st-andrews_ac_uk/Documents/Prominance%20Papers/McLean_2012_ApJ_746_23.pdf)
~ `\cite{McLean_2012ApJ...746...23M}`
 
- Radio survey of ~100 ultracool dwarfs with very large array (VLA)
- Goal to explore the role of rotation in radio activity of ultracool dwarfs
- Found a radio activity-rotation relation with saturation (❓) at <img src="https://render.githubusercontent.com/render/math?math=L_{rad}/L_{bol}\approx 10^{-7.5}"> above <img src="https://render.githubusercontent.com/render/math?math=v\sin i \approx 5 \mathrm{km &nbsp s}^{-1}">
- Their findings support the idea that rotation effect are important for regulating the topology/strength of magnetic fields at least in some fully convective dwarfs
- Positive correlaton between radio to bolometric luminosity and spectral type  
  <img src="https://user-images.githubusercontent.com/9406508/159352447-18989a24-4d76-4305-a734-e1bea64549ae.png" height="300"/>
- Radio to bolometric velocity vs projected rotational velcity trend. Split by spectral type M0-M6, M7-L3. Black dashed line is fit to earlier type objects.  
  <img src="https://user-images.githubusercontent.com/9406508/159353321-a7ed80fa-4b55-4294-85b2-8b9f23f888bd.png" height="300"/>

&nbsp;

##
###
[ADS]() ~
[OneDrive]()
~ `\cite{}`

&nbsp; 
