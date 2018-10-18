# createobject-vfp
I should connect an ERP (developed with vfp) with a PLC system through the ETHERNET protocol
I have the libraries (snap7.dll, snap7.net.dll, snap7.lib) to communicate with the PLC but I cannot create the connection
I copied these DLLs in my project and i have to define the object but i have an error

the system already comunicates with a software in VB and from the syntax Vb I see that we need to create the 'client object' that in the VB form is indicated as follows:
"Dim Client as Snap7.S7Client"

but in vfp how can I replicate this command?

i made this:
LOCAL ocli as snap7.s7client
ocli=CREATEOBJECT("snap7.s7client") 

but i have this error:
class definition snap7.s7client is not found
