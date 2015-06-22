This is a simple python script that accepts a Netscaler cookie (usually starts NSC_) and decrypts the load balancer name and the server IP._

Thanks to:
Alejandro Nolla Blanco - alejandro.nolla@gmail.com - @z0mbiehunt3r - for the inspiration to write this and for adding the error checking.

Daniel Grootveld - danielg75@gmail.com - @shDaniell - for helping with the XOR method of decryption, adding the service port decryption and for making my regex more robust.

Usage:

python nscookiedecrypt.py <Netscaler Cookie>

e.g.  python nsccookiedecrypt.py NSC\_rfse-gesfe-etsgsvs-fseefe=ffffffff3c19594d45525d5f4f58455e445a4a423660