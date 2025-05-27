# Crab Rave Radio
The goal of this project is to implement a music streaming service from scratch **all the way from implementing our own TCP/IP stack**

## The gist of it
As a true crustacean, you love music that involves crabs. But, you also hate UI (and existing solutions)! That means there’s only one solution, which involves building everything yourself. This project is about creating our own network stack, music streaming, splitting your system into multiple services, and hosting it using a kubernetes cluster wherein your rust systems communicate.

Note that ANYTHING YOU NEED should be a package you create yourself. Networking? Implement it. A REST framework? Implement it. Audio streaming? Implement it. Also properly package it. Thanks.

## Documentation purposes
Every research aspect of the implementation is documented here, and maybe some more. It is mostly for myself to keep track of whatever I need to know, but perhaps you'll find use in it as well. That's not the goal though, the goal is fun and adventure.

Since we are using cool names, such that our project sounds even cooler, a terminology map is necessary. See below for the meaning of each crate as defined in the `crates/` folder.


 - Pinchpack
 - TCP/IP stack
 - Clawframe
 - REST framework
 - Sandscuttle
 - Lossy audio streaming
 - CrabDB
 - Database
 - Carapace
 -  inter-service communication provider
 - Crabrave
 - The super cool CLI for the radio
 - {columns="2"}

Note that each crate has their separate documentation section, this makes our lives a bit easier when trying to look back at.