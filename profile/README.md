## Dyumnin Semiconductor's public repo's
Public Domain tool and scripts for various flows and processes used at Dyumnin Semiconductors.
## New account setup.
When you login to a new server clone [setupscripts](https://github.com/dyumnin/setupscripts) and run `sudo setup.sh` to setup the default RC files.
## Accounting Package.
If you are our book-keeper, The account scripts are in [dyu_accounting](https://github.com/dyumnin/dyu_accounting)
## Project Management.
The project management setup consists of 2 components.
1. Use of a custom [taskwiki](https://github.com/jahagirdar/taskwiki) to capture action items.
2. A [bunch of scripts](https://github.com/jahagirdar/tw-pm) to provide a web based GUI for captured tasks and convert taskwarrior tasks to taskjuggler file.

# Reusable IP's for ASIC and FPGA Development.
1. ASIC Cells: Logic that is typically replaced by standard cells during PNR, Clock Muxes, Clock Gates, 2-3 flop synchronizers, reset synchronizers etc.
2. [cocotbext cookiecutter](https://github.com/dyumnin/cookiecutter-cocotbext) Cookiecutter script for setting up development of new cocotb VIP.
## Rescued Abandonware
This is a list abandonware from elsewhere on the web which we have adopted, tested and bugfixed and tapedout.
### Verilog
1. [I2C](https://github.com/dyumnin/verilog-i2c)
2. [SPI_Slave](https://github.com/jahagirdar/axi_spi_slave)
3. [SPI_Master](https://github.com/dyumnin/axi_spi_master)
## Cocotb 
1. [cocotbext-APB](https://github.com/jahagirdar/cocotbext-apb)
2. Also checkout the VIP's developed by [our interns](https://github.com/Dyumnin-Interns)
