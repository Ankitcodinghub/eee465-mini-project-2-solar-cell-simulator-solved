# eee465-mini-project-2-solar-cell-simulator-solved
**TO GET THIS SOLUTION VISIT:** [EEE465 Mini Project 2-Solar Cell Simulator Solved](https://www.ankitcodinghub.com/product/eee465-mini-project-2-solar-cell-simulator-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95678&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EEE465 Mini Project 2-Solar Cell Simulator Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
The goal of the series of mini-projects is to build a model to allow us to calculate and optimize a PV system. In the first project, we re-acquainted everyone with programming, and calculated solar power density and energy on a surface with arbitrary tilt and azimuth. In this project, we will calculate and optimize the efficiency of a solar cell. Mini Project 3 will calculate the power from a module; Project 4 calculates the PV system parameters.

Overview

A solar cell is characterized by the equation:

(𝑉−𝐽𝑅𝑠𝑒𝑟𝑖𝑒𝑠)

𝐽= 𝐽0(𝑒 𝑘𝑇 −1)−𝐽𝐿

In order to calculate its performance, we need to (1) Calculate J0; (2) Calculate JL; (3) Calculate Rseries. Then from these, we can calculate the parameters that define the efficiency. The equations for all of these parameters are in the lecture notes, and also in the more detailed section descriptions below.

𝑉 𝐽 𝐹𝐹 efficiency = 𝑜𝑐 𝑠𝑐

Part 2: Calculate the IV curve parameters: J0, JL and Rseries. As part of this we also calculate the quantum efficiency.

Part 3: Calculate the efficiency parameters VOC, JSC, FF and Pin and calculate efficiency. Part 4: Vary parameters to optimize efficiency.

Part 5: Use your Solar Cell Simulator to Analyze a solar cell.

</div>
</div>
<div class="layoutArea">
<div class="column">
We divide the assignment into five parts:

Part 1: Read in material and solar cell device parameters.

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑃 𝑖𝑛

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Set up your program to read in or acquire the material and device parameters. “Hardwiring” them in the code is OK. The default values for Silicon (Si) are in the table below.

</div>
</div>
<div class="layoutArea">
<div class="column">
Name in Emitter Base Value code Value

MATERIAL PARAMETERS ASSUMED INDEPENDENT OF DOPING

</div>
<div class="column">
Units

cm-3 msec cm-1

cm2/s cm-3 cm/sec

Microns or cm

Microns or cm

cm2/V.s cm6/s

</div>
</div>
<div class="layoutArea">
<div class="column">
N-p or p-n junction

Intrinsic carrier concentration (ni)

Minority carrier lifetime 0

Absorption coefficient ()

Diffusivity (D) Doping (N)

Surface Recombination (S)

Thickness (xj, H)

Diffusion Length (L) Mobility ()

Minority carrier lifetime

Output:

</div>
<div class="column">
ni

ab

DE DB NE NB SE, SB

WE , WB

LE or LB

</div>
<div class="column">
n-type

8.6  109 cm-3 or 1  1010 (first is more accurate, second is more commonly used.)

0 = 1; calculate eff based off of this value and parameters given below in table

Absorption coefficient and AM1.5G spectrum as a function of  in “10_nm_AM15G_absorption.txt”

</div>
</div>
<div class="layoutArea">
<div class="column">
EMITTER AND BASE PARANETERS

</div>
</div>
<div class="layoutArea">
<div class="column">
15 30

1  1018 5  1016

</div>
</div>
<div class="layoutArea">
<div class="column">
500 1

</div>
<div class="column">
1000

300

CALCULATED PARAMETERS

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐿 = √𝐷𝜏𝑒𝑓𝑓

𝐷 = 𝑘𝑇 𝜇𝑞

</div>
</div>
<div class="layoutArea">
<div class="column">
1 𝜏𝑒𝑓𝑓

</div>
<div class="column">
= 𝐶 𝐴𝑢𝑔𝑒𝑟

</div>
<div class="column">
𝑛2 +

</div>
<div class="column">
1 𝜏0

</div>
<div class="column">
𝐶 𝐴𝑢𝑔𝑒𝑟

</div>
<div class="column">
= 1.5 × 10−30

.

</div>
</div>
<div class="layoutArea">
<div class="column">
****** WATCH OUT FOR THE UNITS ******

</div>
</div>
<div class="layoutArea">
<div class="column">
The biggest mistake (by far) I see in debugging is unit errors, which admittedly is not helped by

</div>
</div>
<div class="layoutArea">
<div class="column">
the semiconductor convention of specifying thickness in microns, and all the other parameters in

</div>
</div>
<div class="layoutArea">
<div class="column">
units that use “cm”. If you get strange numbers, first check unit consistency

</div>
</div>
<div class="layoutArea">
<div class="column">
(1) Plot the minority carrier lifetime as a function of doping for the n-type emitter – use a log plot for the x-axis doping and y-axis lifetime. LABEL UNITS!!

(2) Plot the absorption coefficient as a function of wavelength, labelling units and using log plot for .

(3) Print the emitter, base and material parameters in a readable format and compare to tabulated values.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
1. Calculate J0 for a device with the test solar cell parameters and compare with the values in Appendix A: Output of the Python script for the test case. The variation generally comes from two sources: accuracy (significant figures) in physical constants; and variation in material parameters. For example, the most commonly used value of ni in Si is 1  1010 cm-3, but an updated value is 8.6  109 cm-3. You can use either.

For reference, the J0 equation for electrons in p-type material is repeated from the notes below; n- type is the same, expect all hole carrier parameters are used and NA is replaced by ND.

2 𝑆𝑛𝐿𝑛cosh(𝐻)+sinh(𝐻) 𝐽0𝑛 = 𝑞 𝐷𝑛 𝑛𝑖 [ 𝐷𝑛 𝐿𝑛 𝐿𝑛 ]

</div>
</div>
<div class="layoutArea">
<div class="column">
b.

</div>
<div class="column">
the wavelength range.

In Mini Project 1, you read in a file, did a calculation and printed it out, so this is the same except the file you read is the AM1.5G solar spectrum and the calculation is the equation above.

Calculate and plot the quantum efficiency as a function of wavelength in both the emitter and the base of the solar cell as a function of wavelength. The quantum efficiency equations are calculated as functions in the python library called IQE_emitter(ab, We, Le, De, Se)

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐿𝑁𝑆𝐿𝐻𝐻 𝑛 𝐴 𝑛 𝑛sinh( )+cosh( )

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐷𝑛 𝐿𝑛 𝐿𝑛

</div>
</div>
<div class="layoutArea">
<div class="column">
Output: Print the emitter, base and total J0 for the test solar cell and compare to the given value in Appendix A.

2. Calculate JL.

Calculating JL is conceptually straight forward (although computationally long). It is done by:

<ol>
<li>Calculating the number of photons/m2 in each wavelength band in the solar spectrum – this is called photon flux.</li>
<li>Calculating the quantum efficiency at each wavelength, which physically corresponds to the fraction of incident photons converted to current at each wavelength.</li>
<li>Multiplying to two above and adding them all up over all the wavelengths.</li>
</ol>
More details on each of the a,b,c parts from above:

</div>
</div>
<div class="layoutArea">
<div class="column">
a.

</div>
<div class="column">
Calculate the photon flux at each wavelength.

For this, we need to read in the standard solar spectrum (which is the spectral irradiance or the POWER DENSITY per wavelength range). Then we convert it to the number of photons at each wavelength (photon flux) by

Φ𝑖 = 𝑆𝑝𝑒𝑐𝑡𝑟𝑎𝑙 𝐼𝑟𝑟𝑎𝑑𝑖𝑎𝑛𝑐𝑒𝑖 × [Δ𝜆] × 𝜆𝑖 h𝑐

</div>
</div>
<div class="layoutArea">
<div class="column">
Where “i” denotes the wavelength at which the spectral irradiance is given. Please, make sure that you calculate the photon energy h𝑐 in Joules. If you use the expression 1240 ,

</div>
</div>
<div class="layoutArea">
<div class="column">
𝜆𝑖 𝜆𝑖 (𝑛𝑚) you need to multiply the energy in eV by the electron charge q. [Δ𝜆] is the wavelength interval the spectral irradiance corresponds to. However, you need to be careful if the spectral irradiance has already been normalized to 1 nm bin width or already been multiplied by [Δ𝜆]. You need to look at the file header or other information on the units of the spectral irradiance. If you are uncertain, sum the spectral irradiance and compare it to the value of approximately 840 W/m2, which is the integral of the spectral irradiance over

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
c.

</div>
<div class="column">
For Matlab users, copy the equation for these in the definitions into Matlab and define a function around it. One thing you have to change in the equation for Matlab (or other programming languages) is how you call the hyperbolic functions; in python it is np.cosh, so change this for another programming language.

Calculate JL. To find the JL, we multiply the photon flux (part a) by the quantum efficiency (part b), and then sum over all the wavelengths.

𝐽𝐿𝑖 =𝑆𝑝𝑒𝑐𝑡𝑟𝑎𝑙𝐼𝑟𝑟𝑎𝑑𝑖𝑎𝑛𝑐𝑒𝑖 ×[Δ𝜆] ×𝜆𝑖 ×𝑞×𝑄𝐸𝑖 = Φ𝑖 ×𝑞×𝑄𝐸𝑖 h𝑐

Output: Plot JLi as a function of wavelength and in the graph title give the total JL in mA/cm2.

Note 1: In some textbooks or calculations, you may see a similar equation as above in terms of a parameter called spectral response; this is the same basic equation, just calling the last two terms in the equation above the spectral response:

𝑆𝑝𝑒𝑐𝑡𝑟𝑎𝑙 𝑟𝑒𝑠𝑝𝑜𝑛𝑠𝑒𝑖 = 𝑞 𝜆𝑖 × 𝑄𝐸𝑖 h𝑐

To get:

Note 2: if you want to use other absorption coefficients (e.g, you choose to do a different solar cell material), the wavelength at which the absorption coefficient is defined must be

</div>
</div>
<div class="layoutArea">
<div class="column">
and IQE_base(ab, We_Wd, Wb, Lb, Db, Sb). The equations are given in the lecture notes and also repeated below for convenience.

The parameter “α” is the absorption coefficient and is dependent on wavelength (we omitted the (λ) after the α to keep the equations to one line. In the function call in the code it is an array called “ab”. α(λ) is in a file called “10_nm_AM15G_absorption.txt”, which you read into your program in Part 1.

*** We do not use Wd, the width of the depletion region, so use Wd = 0.

Output: The two plots of QE_emitter and QE_base are typically combined into one plot with two lines, so please plot it this way.

</div>
</div>
<div class="layoutArea">
<div class="column">
(𝑆𝑒𝑚𝐿𝑒𝑚+𝛼𝐿𝑒𝑚)−𝑒−𝛼𝑥𝑗(𝑆𝑒𝑚𝐿𝑒𝑚 cosh(𝑥𝑗 )+sinh(𝑥𝑗 ))

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑄𝐸 (λ) = 𝛼𝐿𝑒𝑚 _𝑒𝑚𝑖𝑡 22

</div>
<div class="column">
𝐷𝑒𝑚

</div>
<div class="column">
𝐷𝑒𝑚 𝐿𝑒𝑚 𝐿𝑒𝑚 −α𝐿

</div>
<div class="column">
𝑒−α𝑥𝑗

]

</div>
</div>
<div class="layoutArea">
<div class="column">
(𝛼𝐿𝑒𝑚−1)

</div>
<div class="column">
𝑥 𝑥 𝑒𝑚 𝑆𝑒𝑚𝐿𝑒𝑚sinh( 𝑗)+cosh( 𝑗)

</div>
</div>
<div class="layoutArea">
<div class="column">
[

</div>
<div class="column">
𝐷𝑒𝑚 𝐿𝑒𝑚 𝐿𝑒𝑚

𝑆𝑏𝐿𝑏(cosh(𝐻)−𝑒−α𝐻)+sinh(𝐻)+𝛼𝐿 𝑒−α𝐻

</div>
<div class="column">
]

</div>
</div>
<div class="layoutArea">
<div class="column">
−α𝑥′

𝛼𝐿𝑏𝑒𝑗𝐷𝑏𝐿𝑏 𝐿𝑏𝑏

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑄𝐸_𝑏𝑎𝑠𝑒(λ)= 22 [𝛼𝐿𝑏− 𝑆𝐿 𝐻 𝐻

</div>
</div>
<div class="layoutArea">
<div class="column">
(𝛼 𝐿𝑏−1) 𝑏 𝑏sinh( )+cosh( ) 𝐷𝑏 𝐿𝑏 𝐿𝑏

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐽𝑠𝑐𝑖 = 𝐽𝐿𝑖 = 𝑆𝑝𝑒𝑐𝑡𝑟𝑎𝑙 𝐼𝑟𝑟𝑎𝑑𝑖𝑎𝑛𝑐𝑒𝑖 × 𝑆𝑝𝑒𝑐𝑡𝑟𝑎𝑙 𝑟𝑒𝑠𝑝𝑜𝑛𝑠𝑒𝑖

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
the same wavelength at which the spectral irradiance is defined. Since the absorption coefficient and spectral irradiance don’t in general have the same wavelength spacing, we have to convert either the absorption or the spectral irradiance to the same wavelength interval. We did this already for the files we handed out.

Output: Print the emitter, base and total JL for the test case.

3. Calculate the emitter series resistance. In the notes, we calculate multiple terms of the series resistance; for simplicity, here we only calculate the emitter series resistance. The area-normalized series resistance is given by the equation:

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑅≈𝑅 =𝜌𝑆2 𝑠𝑒𝑟 𝑒𝑚𝑖𝑡𝑡𝑒𝑟  12

and 𝜌 is the sheet resistance of the emitter calculated by the equation: 𝜌=𝜌= 1 1

where We is the emitter thickness, N is the emitter doping, and  is the mobility in the emitter.

We have set S = 0.2 cm corresponding to a typical value for a commercial silicon grid. If you want to see the optimization of the top metallization from which we get this value, it is at: http://www.pveducation.org/pvcdrom/5-design-of-silicon-cells/optimization-of-finger-spacing.

The python library has two function definitions which calculate the sheet resistivity and emitter series resistance for you. They are: def emitter_resistance(Sf, Rsheet): and def sheet_resistivity(doping, thickness):

Output:

(1) Print out the series resistance (including units) and compare to test case.

(2) Plot the IV curve, labelling the graph.

(1) Calculate JSC using JSC = JL. Unless the series resistance is very high (in which case we aren’t using the solar cell anyway), the current at V=0 (which is how JSC is defined) is the same as JL.

Note: If you are bored or writing the code in a more general fashion, you can find JSC from:

(𝐽𝑆𝐶𝑅𝑠𝑒𝑟𝑖𝑒𝑠)

𝐽𝑆𝐶 = 𝐽0(𝑒 𝑘𝑇 −1)−𝐽𝐿

This equation is solved recursively (you can’t solve exactly in closed form), which is the reason we typically ignore it.

</div>
</div>
<div class="layoutArea">
<div class="column">
where

</div>
</div>
<div class="layoutArea">
<div class="column">
S is the finger spacing (NOT the surface recombination velocity – semiconductor notation

</div>
</div>
<div class="layoutArea">
<div class="column">
is terrible!)

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑊 𝑞𝜇𝑁𝑊 𝑒𝑒𝑒

</div>
</div>
<div class="layoutArea">
<div class="column">
(2) Calculate Voc using:

(3) Calculate FF of the IV curve.

</div>
<div class="column">
𝑉𝑜𝑐= 𝑘𝑇𝑙𝑛(𝐽𝑆𝐶) 𝑞 𝐽0

</div>
</div>
<div class="layoutArea">
<div class="column">
The FF is defined as the voltage and current where the power (P=V x I) is the largest. We can find this value one of two ways:

• Trace out the IV curve and find at what values of V and I the power is the largest. Advantage: you need the full IV curve in another mini-project, so might as well do it now. Disadvantage: Longer to compute (not important now but depending on what you

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
are doing in your final project, it might be an issue).

• Use the closed form for FF from the two equations below:

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐹𝐹 = 𝑣𝑜𝑐−ln(𝑣𝑜𝑐+0.72) where 𝑣

0 𝑣𝑜𝑐+1 𝑜𝑐

</div>
<div class="column">
= 𝑞 𝑉 , n being the ideality factor and 𝑛𝑘𝑇 𝑜𝑐

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐹𝐹=𝐹𝐹 (1−𝑅𝑠𝑒𝑟) where 𝑅

0 𝑅𝐶𝐻 𝐶𝐻

</div>
<div class="column">
=𝑉𝑀𝑃 ≈𝑉𝑂𝐶 𝐼𝑀𝑃 𝐼𝑆𝐶

</div>
</div>
<div class="layoutArea">
<div class="column">
(4) Calculate the efficiency. and the impact of the maximum power point &amp; FF.

𝐽 𝑉 𝐹𝐹 𝑒𝑓𝑓𝑖𝑐𝑖𝑒𝑛𝑐𝑦 = 𝜂 = 𝑆𝐶 𝑂𝐶

Where P is the incident power density. Since we are using the AM1.5G spectrum, it is 1000 W/m2 (or equivalently 0.1 W/cm2), but if you are generalizing the program, you should calculate it from the input spectrum.

Output: Print Voc, Fill Factor and Efficiency.

The goal of this part of the problem is to optimize the solar cell, changing only the emitter doping and

emitter thickness.

IMPORATANT: The maximum emitter doping you should use is Nemitter = 1  1020 cm-3. Values above this will give higher efficiency in the calculations, but the equations for minority carrier lifetime do not adequately work for such high doping – in practice the minority carrier lifetime is so low at higher doping that the material is not particularly electrically active. The minimum thickness of the emitter should be 100 nm – below this in practice the solar cell is subject to shunting.

Output:

(1) Emitter doping and thickness, JSC, VOC, FF, and efficiency for the maximum efficiency.

(2) Justify that your answer is the optimum. You can do a plot of efficiency vs doping and thickness; you can describe how you optimized it and what changed and why it makes sense; or you can prove it’s the optimum in other ways. You cannot say “this is what my program spit out”. Basically, any time you give an optimum result for an engineering problem, you have to also show that your answer is reasonable and correct.

Note: your optimum may not be the same as someone else’s given different values of ni or number of data points, etc. Not that you should be comparing your answer to other people’s, but we are not expecting a single answer (design problems rarely have a single correct answer).

The goal of this part of the problem is to analyze what the losses are in the solar cell, and how we might improve the solar cell. Parameters you can look at are the quantum efficiency, compare J0 from the emitter and from the base. You can plot different parameters (JSC, VOC) as function of doping and thickness. You can change a material parameter and see what its effect is.

Output:

Give the material and device parameters which are key in limiting the device efficiency. From this, suggest some approaches to increasing cell efficiency.

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑃 𝑖𝑛𝑐𝑖𝑑𝑒𝑛𝑡

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
This is just for you to check if your Python installation works or if your code in Excel or Matlab produces realistic values for the test case.

emitter diffusion length (cm) 0.00387104830569

base diffusion length (cm) 0.0925820099773

emitter resistivity (ohm/sqr) 208.0503042999924

series resistance (ohm.cm2) 0.6935010143333081

light generated current density in emitter (A/cm2) 0.012054716461 light generated current density in base (A/cm2) 0.0268994750224 total light generated current density (A/cm2) 0.0389541914834

J0 emitter (A/cm2) 7.08712167027e-15 J0 base (A/cm2) 1.32750778369e-13 J0 total (A/cm2) 1.39837900039e-13 Voc 0.677074345174

FF without series resistance 0.842761558955 FF with series resistance 0.806066612651 Efficiency (%) 21.2599131551

</div>
</div>
</div>
