# Origin of the Dataset

This project looks at some data from the US National Bridge Inspection maintained by the Federal Highways Agency (FHWA), part of the US Department of Transportation. The original data comes from the [National Bridge Inspection](https://www.fhwa.dot.gov/bridge/nbi/ascii.cfm) section of the FHWA's web site. However, it has been greatly simplified. If you are interested in a particular bridge, you can use the structure number to look it up (including on google maps, where the satellite imaging shows a picture) on the (Info Bridge System)[https://infobridge.fhwa.dot.gov/].

**The aim of the Bridge Inspection programme is to check on the state of bridges so that necessary repairs can be carried out. If this is not done, a bridge can fail. The dataset has information about the bridges and the condition given in the most recent inspection.**

* The FHWA's database covers the whole USA. Our data is only for the state of Texas. 
* As well as bridges, the FHWA's database covers tunnels (there seem to be no highway tunnels in Texas) and 'culverts'. A culvert is a form of drain, allowing water to pass under a highway. The culverts have been removed, leaving only the bridges.
* All of the bridges carry a highway (that is, a road runs over the bridge). What is underneath varies: another road, a waterway or a railway are among the possibilities. 

# Analysis Goals

As part of this exercise, we imagine the management of the Texas Department of Transportation wishes to investigate the use
of the following variables to predict the current condition of bridges:
1. Age (derived from variable Year)
2. average use (variable AverageDaily)
3. percent trucks (variable Trucks_percent)
4. material (variable Material)
5. design (variable Design) <br>

The current condition is derived from variables Deck_rating, Superstr_rating and
Substr_rating of the bridges. They wish to know: <br>
1. How well the proposed variables can predict the bridge condition. <br>
2. Which of the proposed variables has more influence on the current condition. <br>

The use of regression has been agreed in advance.
Your report is to be submitted to a representative of the Texas Department of
Transportation. She is a specialist in metal corrosion and the deterioration of concrete and
wants to understand “what the data says” but also “how you have processed it” (for
example so that she can check that your assumptions are sensible). She is not interested in
understanding how your code works. She understands that you do not have a detailed
knowledge of bridges (or corrosion) so will be content provided that any assumptions you
have made are clearly explained: if any of them turn out to be inappropriate she can ask you
to modify the analysis.
