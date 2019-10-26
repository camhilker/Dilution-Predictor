## Dilution-Predictor

This is a Shiny app that I created for potential application in a microbiological testing laboratory.
A 1/10 dilution is typically applied when enumerating a product or swab for potential microbial pathogens.
This app is to predict when a higher dilution may be needed (indicated by an increased level of microbes within the sample),
based on past client data.

This was to fulfill a need for accurate prediction in the plating step when turn-around-time is crucial. 
If a 1/10 dilution is applied to a sample that contains a high microbial count, 
the plate cannot be read after incubation and the sample must be retested, resulting in up to a 5 day delay of result submission.
This issue is further compounded in environmental samples where the area must be reswabbed by the client and submitted again.
Use of this app can reduce error in the plating step and reduce supply use by targeting the correct dilution needed for the client and product type.

The included data file is mock data that I created to feed into the app.
The example test codes refer to the following:

__APCPFSWCMMEF__ - Standard aerobic plate count (using 3M petrifilm) for an environmental swab, as described by CMMEF*<br>
__APCPFSPCMMEF__ - Standard aerobic plate count (using 3M petrifilm) for an environmental sponge, as described by CMMEF<br>
__COLIPFSPCMMEF__ - Coliform plate count (using 3M petrifilm) for an environmental sponge, as described by CMMEF<br>
__LABPFCMMEF__ - Lactic acid bacterial count (using 3M petrifilm), as described by CMMEF<br>
__ENTBACPFCMMEF__ - Enterobacteriaceae plate count (using 3M petrifilm), as described by CMMEF<br>
__APCPFAOAC__ - Standard aerobic plate count (using 3M petrifilm), as described by AOAC*<br>
__COLIPFAOAC__ - Coliform plate count (using 3M petrifilm), as described by AOAC<br>
__STAPHAPFAOAC__ - Staphylococcus aureus plate count (using 3M petrifilm), as described by AOAC<br>
<br><br>
*CMMEF = Compendium Methods Microbiological Examination Foods<br>
*AOAC = Association of Official Analytical Chemists
