# ColorMagDiagrams

This project creates interactive and static color-magnitude diagrams (CMDs) for ultracool dwarfs and exoplanets based on photometric and parallax data. The CMDs can be customized to highlight specific targets, compare observed values to model predictions, and visualize potential exoplanet hosts.

---

### Data Source and Acknowledgements

This work uses data from **The UltracoolSheet**, available at [http://bit.ly/UltracoolSheet](http://bit.ly/UltracoolSheet), maintained by:

> Will Best, Trent Dupuy, Michael Liu, Aniket Sanghi, Rob Siverd, and Zhoujian Zhang

and developed from compilations by:

- Dupuy & Liu (2012, *ApJS*, 201, 19)  
- Dupuy & Kraus (2013, *Science*, 341, 1492)  
- Deacon et al. (2014, *ApJ*, 792, 119)  
- Liu et al. (2016, *ApJ*, 833, 96)  
- Best et al. (2018, *ApJS*, 234, 1)  
- Best et al. (2021, *AJ*, 161, 42)  
- Sanghi et al. (2023, *ApJ*, 959, 63)  
- Schneider et al. (2023, *AJ*, 166, 103)

**For proper acknowledgements, please cite the UltracoolSheet as indicated above.**

---

### 🧩 Custom Data Integration (`_customValues.ipynb`)

The `_customValues` file enables users to overlay their own data on the interactive CMD plot. There are two supported modes:

#### 1. Spectra Input
- Place compatible spectra files in the `spectra/` folder.
- These will be automatically analyzed using the **Species** library.
- The object's **J–K (MKO) color** and **absolute J-band magnitude** will be extracted and plotted.
- Highlighted targets will be shown alongside the full ultracool dwarf population.

#### 2. Manual Input
- Enter photometric values (e.g., J–K color and absolute J-band magnitude) directly in the `_customValues.ipynb` file where appropriate.
- These will appear in the interactive plot, allowing side-by-side comparison with journal-published values.

