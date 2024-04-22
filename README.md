# RISC-V-CPU-with-15-instructions
## This project is my  computer composition principle homework,it contains 15 instructions of RISC-V instruction set.15 instructions are the following:
### lui -----rd<-imm||000H
### addi -----rd<-(rs1)+SExt(imm)
### ori -----rd<-(rs1)|ZExt(imm)
### add -----rd<-(rs1)+(imm)
### sub -----rd<-(rs1)+(imm)
### sll -----rd<-(rs1)+(imm)
### slt -----rd<-(rs1)+(imm)
### sltu -----rd<-(rs1)+(imm)
### sra -----rd<-(rs1)+(imm)
### lb -----rd<-SExt(M[(rs1)+SExt(imm)]~8b~  )
### lw -----rd<-M[(rs1)+SExt(imm)]~32b~
### sw -----M[(rs1)+SExt(imm)]~32b~<-(rs2)
### beq -----if((rs1)==(rs2))PC<-(PC)+SExt(imm<<1)
### blt -----if((rs1)<~unsigned~(rs2))PC<-(PC)+SExt(imm<<1)
### jal -----rd<-(PC)+4;PC<-(PC)+SExt(imm<<1)

## You may find the quartus project in the file "CPU"
