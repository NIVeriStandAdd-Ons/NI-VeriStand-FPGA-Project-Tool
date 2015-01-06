## NI VeriStand FPGA Project Tool ##

**NI VeriStand FPGA Project Tool** guides one through the process of selecting the FPGA and any C-Series modules that may be contained within a cRIO or C-Series Expansion Chassis. It operates similar to the wizard for starting a new LabVIEW FPGA Project except that it adds the necessary components to the project for a custom FPGA to be used with NI VeriStand. The project wizard adds a framework template, DMA FIFOs, and corresponding XML file to begin development. It also saves the project and files to a location specified by the user.

After installing the NI VeriStand FPGA Support, NI VeriStand RIO Library will appear on the FPGA function’s palette. The NI VeriStand RIO Library was created so that creating a custom FPGA bitfile for NI VeriStand will be less cumbersome and not require LabVIEW FPGA expertise. Each C-Series module with the exception of communication modules (CAN, Profibus, etc.), motion modules, removable storage modules, and some third-party modules has been included in the NI VeriStand RIO Library. The modules are separated between Basic I/O and Special Case I/O. You can drop these VIs into the template and wire them up directly to DMA.

More details can be found on the [community post](https://decibel.ni.com/content/docs/DOC-13815) for this IP.

### LabVIEW Version ###

LabVIEW 2010

### Quality, Limitations ###

This code was developed in 2011 and has been in use worldwide since then. It should be considered mature and high quality. However, the installer is a bit strange, and ideally it would be redeveloped to use VI package manager. Additionally, the example is installed into user.lib, which is wrong.

### License ###

Copyright (c) 2011, National Instruments

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

- Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
- Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
- Neither the name of the National Instruments Corporation nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
