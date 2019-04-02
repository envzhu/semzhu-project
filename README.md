## * Work in progress
# Semzhu Project
### Overview
Secure embedded system on hypervisor; Make embedded system more secure by extending hypervisor.
You can run the whole system on [qemu4semzhu](https://github.com/envzhu/qemu4semzhu), a special qemu for Semzhu Project.
- Semzhu-Visor; A small embedded hypervisor for AArch64 runnning on an emulator
  - As far as I know Semzhu-Visor is the first as an embedded hypervisor which virtualizes CPU exceptions and IRQ interrupts.
- A implementation method of security modules for embedded systems by CPU insrruction virtually extension using hypervisor 
- Two detection modules as examples by CPU insrruction virtually extension
  - Anti-ROP on Semzhu
  - Anti-COP on Semzhu

### Source code links to the Results 
- [Semzhu-Visor](https://github.com/envzhu/semzhu-visor)
- [qemu4semzhu](https://github.com/envzhu/qemu4semzhu)
- [kozos-aarch64-semzhu](https://github.com/envzhu/kozos-aarch64-semzhu)

## Acknowledgments
Semzhu Project is the result of research and development in SecHack365(*1).
Especially, I thank Sakai Hiroaki, my mentor and who leads me to 'Embedded World'.Without him, this project wouldn't be.   
*1 [SecHack365](https://sechack365.nict.go.jp/) ... A Japanese security hackathon for a year in order to train security innovators.

## Author
Zhu Yiwen (@envzhu)
