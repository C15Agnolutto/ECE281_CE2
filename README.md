ECE281_CE2
===========
### Post-CE Analysis
I created the add3.vhd and inverter.vhd files with no errors. During the creation of my Decoder_Structural.vhd file,
I made parse error in the 'begin' scetion while defining my I0_inv and I1_inv port assignments; I had an apstrophe in
the name which had to be removed. My syntax check came up clear for my CE2_testbench.vhd; however, when I simulated the 
decoder, my results did not seem to match what was provided in the CE2 document. After a quadruple debugging check
of all my .vhd files, I found that my results were actually correct but I had placed my testbench cycle in a different
order. I reordered my testbench cycle to match the one provided to make grading easier. I had no errors creating the
Decorder_Behavioral.vhd file or the Decorder_Behvioral_testbench.vhd files. My results were similar for both the 
structural and behavioral formats; they can be seen below. 


### Structural Testbench Waveform
![struct] 


### Behavioral Testbench Waveform
![beh] (https://raw2.github.com/C15Agnolutto/ECE281_CE2/master/Behavioral_testbench.JPG)


### Conclusion
