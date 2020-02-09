# ca_wrapper
A set of scripts to make it easy to create and use openssl-based Certificate Authorities (root and chains of intermediates)

Portions adapted from the excellent jamielinux.com/docs/openssl-certificate-authority/index.html.

I started this project while working at SUNY Potsdam. We had dozens of SSL 
certs signed by commercial certificate authorities that were internal-use 
only. We also had a problem with self-signed certs installed by previous 
sysadmins with no established naming conventions and breakage when they 
expired.

This project was meant as a cost- and hassle-saving means to allow 
myself and other sysadmins the ability to set up CAs as needed (lots of 
different environments) and make it easy to manage internal-only certs while
following naming conventions. Unfortunately I was unable to complete and deploy
to production due to other project priorities.

At the time there were other FOSS projects that tackled the same problem but 
were overkill for our needs. Haven't needed this or looked at it since
leaving Potsdam. There's probably better stuff available now.
