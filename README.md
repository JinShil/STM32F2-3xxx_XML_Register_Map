# STM32F2-3xxx_XML_Register_Map
STM32F42xxx and STM32F43xxx registers in XML format intended for use in memory mapped I/O code generation

This source documentation for the register maps came from the [STM32F429/439 reference manual](http://www.st.com/web/en/resource/technical/document/reference_manual/DM00031020.pdf).  Memory addresses can be obtained from the [STM32F42xxx datasheet](http://www.st.com/web/en/resource/technical/document/datasheet/DM00071990.pdf) and [STM32F43xxx datasheet](http://www.st.com/web/en/resource/technical/document/datasheet/DM00077036.pdf).

This repository, only contains data for registers relevant to the STM32F42xxx and the STM32F43xxx MCUs.

I wrote a program that allows one to cut and past text from the .pdf file and generate this XML, with some manual tweeking.  A version of that program is published at https://github.com/JinShil/stm32_datasheet_to_d.

Status
------
None of this data has yet been tested or verified for accuracy.  I hope that will change soon after I generate some code from this data and run a test the resulting software.

Licensing
---------
See the LICENSE file for licensing information.
