# lupIO
lupIO screen test
6/11: 
  install enviroments
  compiled linux boot elf. 
6/13: 
  editting riscv_soc repo so that /tb compiles.
(Since the quarter just ended, I unfortunately have many plan these few days. So I will just leave my ideas here for now and will go into it later if needed.)
ideas:since riscv_soc already includes a UART @92, what I need to do is just 
  1.add RAM pool in the tb.(risc_soc says its Ram is external from the design) Hopfully it makes resv_soc capable to boot linux in simulation redirected to a /dev/tty with the core it's using now. 
  2.reaplce the core with biriscv.
