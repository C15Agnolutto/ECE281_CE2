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
![struct] (https://raw2.github.com/C15Agnolutto/ECE281_CE2/master/Structural_testbench.JPG)


### Behavioral Testbench Waveform
![beh] (https://raw2.github.com/C15Agnolutto/ECE281_CE2/master/Behavioral_testbench.JPG)


### Conclusion
This computer exercise allowed me to get practice with structural and behavioral VHDL programming, which in turn gave
me a better understanding of the difference between the two. I succeeded in making a simple decoder in both programming
styles. After a bit of research I found that a decoder allows you to make multiplexors. You can also use a decoder
for the AND pland in your own logic circuits and just leave unconnected the outputs you do not need. Decoders are used 
to decode addresses for memory in computers. 
