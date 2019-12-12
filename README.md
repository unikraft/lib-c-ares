c-ares for Unikraft
===================
This is a port of c-ares to Unikraft. You will need newlib and lwip
for it to work, so please ensure you add the following line to the
LIBS variable in the Makefile:

   ...$(UK_LIBS)/lwip:$(UK_LIBS)/newlib:$(UK_LIBS)/c-ares...
		 
Please refer to the `README.md` as well as the documentation in the `doc/`
subdirectory of the main unikraft repository for further information.
