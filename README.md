# Machine-Listening-Max-Patch
The files of my project can be found here: https://github.com/Damianakoss/Machine-Listening-Max-Patch

This project was inspired by reading the section on "Machine Listening" in Christopher Cox's _Sonic Flux_ in conjunction with doing the Kadenze Course on "Machine Learning for Musicians and Artists". My idea was to create a powerful, flexible, and simple to use audio feature extractor that can be smoothly incorporated in as a module within a multimedia art system regardless of the input sound and the output destination.
The patch is built using objects from the FluCoMa toolkit that can be found here: https://www.flucoma.org/download/ , as well as with some custom gen objects that can be found in the folder.
As soon as every external is on the search path of Max (i.e. in the same folder) the main patch (My_Listening_Machine_Main_Patch.maxpat) is ready to run. Choose your audio  input device, organise the list of features you would like to use, fine-tune the smoothing, define the receiving port of Wekinator, and you can train your ML model in Wekinator. Feel free to try how it works with an input and output combination that is available to you.
