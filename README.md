# ca_wrapper
A set of scripts to make it easy to create and use openssl-based Certificate Authorities (root and chains of intermediates)

Portions adapted from the excellent jamielinux.com/docs/openssl-certificate-authority/index.html.

I started this project while working at SUNY Potsdam. We had dozens of SSL 
certs signed by commercial certificate authorities that were internal-use 
only. This project was meant as a cost- and hassle-saving means to allow 
myself and other sysadmins the ability to set up CAs as needed (lots of 
different environments) and manage internal-only certs.

At the time there were other projects that tackled the same problem but 
were overkill for our needs. Haven't needed this or looked at it since
leaving Potsdam. There's probably better stuff available now.
