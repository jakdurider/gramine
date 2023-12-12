How to build and run
===================

Prepare SGX-available machine.

Build gramine application as described in https://gramine.readthedocs.io/en/stable/

Build the project:

    $ make SGX=1

Run the project:

    $ gramine-sgx bfs -g 10 -n 1 -v -l

You can just add "gramine-sgx" to run "bfs" application inside enclave.
All options are same with usual.
