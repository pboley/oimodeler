# oimodeler

#### A modular modelling tool for optical interferometry

Modules:
* **oimModel** : Create models with various components as bricks 
* **oimData** :  Handle interferometric, spectroscopic and photometric data
* **oimDataFilter** : Filtering and modifying data (wavlengths range cut, smoothing, removing flags...)  
* **oimSiumlulator** : Main class holding evertyhing together and producing final results :plots, tables...
* **oimFitter** : Define and perform model-fitting   
* **oimPlot** : Plotting tools
* **oimUtils** : Various utility for optical-interferometry


>:warning: In early development!  
>* oimModel: Working with gray and chromatic models defined in Fourier plane   
>* imData class: No filtering, no optimization of data      
>* oimSiumlulator: Simulated data and chi2 computation (no filtering no flagging yet)    
>* oimPlot: Basics plots of oifits data (see example below)    
>* oimUtils: Spatial frequencies, baseline name, length and PA    



#### Various example scripts are available in the examples directory. 

Here is the resulting plot from the createModelChromatic.py script.
![boo](./images/createModelChromatic.png)
 
Here is the resulting plot from the oimodel_Create_simulator_data.py script.    
It plots data of a partly resolved binary created with:
- the [ASPRO](https://www.jmmc.fr/english/tools/proposal-preparation/aspro/) software from JMMC (including realistic noise)
- oimodeler using a shifted uniform disk + unresolved component
![boo](./images/oimodel_Create_simulator_data.png)


