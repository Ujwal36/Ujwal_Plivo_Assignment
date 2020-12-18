# Ujwal_Plivo_Assignment
Plivo Assignment

This repo contains:

1. SIPp XML scenario files(3) to register and call.
2. Perl script that triggers the SIPp XML scripts.
3. Logs(generated from above files) and pcaps.

Other details:


To run the perl script, make sure to provide the necessary details in the file: script.pl. For example: IPV4 address of UAC and UAS, credentials of sipp servers, etc.

Make sure to run on a linux machine equipped with latest sipp and perl installed.
Make sure to install Net::SSH::Perl using "cpan -f install Net:SSH:Perl".

To install cpan provide: "yum install cpan" on Fedora or debian linux, For example. Use apt-get otherwise.

