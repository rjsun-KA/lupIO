# lupIO
lupIO screen test.
#### reference:
* Github: fpga_test_soc ([https://github.com/ultraembedded/fpga_test_soc](https://github.com/ultraembedded/fpga_test_soc))
* Github: riscv_soc ([https://github.com/ultraembedded/riscv_soc](https://github.com/ultraembedded/riscv_soc))
## 6/11: 
  * install enviroments
  * compiled linux boot elf. 
## 6/13: 
  * editting riscv_soc repo so that /tb compiles.
## ideas:
(Since the quarter just ended, I unfortunately have many plan these few days. So I will just leave my ideas here for now and will go into it later if needed.)

Since riscv_soc already includes a UART @92, what I need to do is just:

  #### 1.add RAM pool in the tb.
   risc_soc says its Ram is external from the design, so maybe I can add it besides the design in the tb. 
  
   Hopfully it makes resv_soc capable to boot linux with the core it's using now in simulation redirected to a /dev/tty.
  
  #### 2.reaplce the core with biriscv.
