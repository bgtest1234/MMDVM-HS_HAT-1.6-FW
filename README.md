# MMDVM-HS_HAT-1.61-FW,HS_HAT,for pi-star compatible

sudo stm32flash -v -w mmdvm_f1.bin -g 0x0 -R -i 20,-21,21:-20,21 /dev/ttyAMA0
