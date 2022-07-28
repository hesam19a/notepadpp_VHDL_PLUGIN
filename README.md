# notepadpp_VHDL_PLUGIN
VHDL Plugin for the Notepad++ Editor(64bit)

This code is based on http://sourceforge.net/projects/nppvhdlplugin/ sources and https://sourceforge.net/projects/nppvhdl/ ideas.
The first one has only 4 commands and is case sensitive and the second one works only on npp 32bit versions. I've got the available source code and ideas from the mentioned links and created a new VHDL Assistant Plugin for notepad++ 64 bit.
I'm working on this project and this is the first release.

Important:
For using this plugin, Import dll file from notepad++ Setting-->Import-->Import Plugin(s) menue. You should copy the 4 testbench templates(*.vhd files) and the header template(*.txt file) to the plugins folder of notepad++(for me this is in C:\Program Files\npp.7.8.bin.x64\plugins).

You may modify header template and test bench templates for your applications. Please note that there is two lines in header template file that must be unchanged. I will create a manual on how to modify these templates.
QUICK START: select the desired entity in your code and then use copy vhdl entity. Then you can inser component, instantiation, signals, architecture and test benches for this entity using the related plugin command. You may access the plugin commands from Plugins-->VHDL Assistant menue. Inserting process, entity and file header commands are independent from vhdl copy entity command. For header information can be modified from tmp_header.txt and test bench templated can be modified from tmp_testbenchX.vhd files. 
