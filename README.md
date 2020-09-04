
Research
    1. Cryptography 
        a. https://cryptopals.com/ - Very practical challenges
        b. https://mrajacse.files.wordpress.com/2012/01/applied-cryptography-2nd-ed-b-schneier.pdf - Broad background. Good balance between theory and practice
    2. Embedded RE and Vuln Research 
        a. https://microcorruption.com/login 
    3. Linux RE and Vuln Research 
        a. Easy - https://exploit-exercises.lains.space/nebula/
        b. Medium - https://exploit-exercises.lains.space/protostar/
        c. Hard - https://exploit-exercises.lains.space/fusion/ 
    4. Ghidra 
        a. https://www.shogunlab.com/blog/2019/04/12/here-be-dragons-ghidra-0.html
        b. Write a processor module for a processor of your choosing (maybe python byte code?)
    5. Microarchitecture and Vulnerabilities 
        a. Read about SGX, uCode, Hyper Threading
        b. Read about Spectre, Meltdown, ZombieLoad, LVI, Foreshadow
        c. Implement an SGX enclave that protects some secret (the secret and the API is up to you), and extract the secret using a micro-architectural vulnerability or a side channel. Use https://github.com/jovanbulck/sgx-tutorial-space18 as a reference if you want an example for both.

Hardware
    1. Hardware for software engineers 
        a. https://www.khanacademy.org/science/electrical-engineering - Nice intro. Skip the math if it isn’t interesting
        b. https://www.udemy.com/course/fpga-embedded-design-verilog/ 
        c. https://learn.sparkfun.com/tutorials/pcb-basics/all
        d. https://learn.sparkfun.com/tutorials/electronics-assembly 
        e. https://learn.sparkfun.com/tutorials/how-to-read-a-schematic
        f. https://learn.sparkfun.com/tutorials/using-eagle-schematic
        g. https://learn.sparkfun.com/tutorials/using-eagle-board-layout
        h. https://learn.sparkfun.com/tutorials/designing-pcbs-advanced-smd
        i. https://www.sparkfun.com/news/2116
        j. https://www.jeremyblum.com/category/eagle-tutorials/ - Tutorial for Eagle scehmatics
        k. https://www.computeraideddesignguide.com/eagle-pcb-tutorials-design-exercises/ 
    2. Digital signal processing and RF 
        a. https://www.coursera.org/learn/dsp - Full DSP course
        b. Read about GPS (Kaplan, ICD, …)
        c. Download https://sourceforge.net/projects/gnss-sdr/files/data/2013_04_04_GNSS_SIGNAL_at_CTTC_SPAIN.tar.gz   This will get you the file 2013_04_04_GNSS_SIGNAL_at_CTTC_SPAIN.dat, which contains 100 seconds of raw GNSS signal samples collected by an RF front-end centered at 1,575.42 MHz, that was delivering baseband samples at 4 MS/s, in an interleaved I&Q 16-bit integer format.
        d. Try to extract as much info about the GPS sats (num of vis sats, PRs, bits, PRNs, etc..) in the samples as you can. Use GNSS-SDR as a reference. For any questions
