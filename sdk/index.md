---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---
### What is Open Enclave SDK? 
<div class="row2">
<div class="column2" align="justify">
Confidential computing is an ongoing effort to protect data throughout its lifecycle at rest, in transit and now in use.  With the use of Trust Execution Environments, customers can build applications that protect data from outside access while in use. Open Enclave SDK is an open source SDK targeted at creating a single unified enclaving abstraction for developer to be build Trusted Execution Environment (TEEs) based applications.  As TEE technology matures and as different implementations arise, the Open Enclave SDK is committed to supporting an API set that allows developers to build once and deploy on multiple technology platforms, different environments from cloud to hybrid to edge, and for both Linux and Windows.</div>
<div class="column2">
<img  style="float:right; " src="../assets/images/OpenEnclave.png" width="150"  /></div>
</div>
<hr/>
<p style="clear: both;"></p>
### Trusted Execution Environment(TEE) Based Application Development
<div class="row2">
<div class="column2">
<img style="float:left"  src="../assets/images/TEE.png" width="500" /></div>
<div class="column2" align="justify">
An enclave application partitions itself into two components (1) an untrusted component (called the host) and (2) a trusted component (called the enclave).  The host component runs unmodified on the untrusted operating system, while the trusted component runs within the enclave, the protected container provided by a TEE implementation.  These protections allow enclaves to perform secure computations with assurances that secrets will not be compromised.</div>
</div>
<hr/>


### Core Tenets
<div class="row3">
  <div class="column3" ><img src="../assets/images/Universal.png" width="50" /><h4 >Universal</h4><p>Generalize enclave application model to minimize hardware/software specific concepts</p></div>
  <div class="column3center" ><img src="../assets/images/Pluggable.png" width="50"/><h4>Pluggable</h4><p>Componentization to support desired runtimes and crypto libraries</p></div>
   <div class="column3"  ><img src="../assets/images/Standardized.png" width="50" /><h4>Standardized</h4><p>Remove hardware vendor specific signing and verification requirements</p></div>
  </div>
<div class="row3">
   <div class="column3"><img src="../assets/images/Multiplatform.png" width="50" /><h4>Multi-platform</h4><p>Design with all software platforms, Windows and Linux, in mind</p></div>
   <div class="column3center"> <img src="../assets/images/Compatible.png" width="50" /><h4>Compatible</h4><p>Easier enablement of redistributable applications</p></div>
   <div class="column3"><img src="../assets/images/Open.png" width="50" /><h4>Open</h4><p>Open source and a standard for secure enclave-based application development</p></div>
</div>
<hr/>

### Supported SDK Functionality
<div class="row2">
  <div class="column2" align="justify"><h4>&#10004;Enclave creation and management</h4><p>Function calls to manage the lifecycle of an enclave within your application</p></div>
  <div class="column2right" align="justify"><h4>&#10004;Enclave measurement and identity</h4><p>Expressions of enclave measurement and identity</p></div>  
</div>
<div class="row2">
  <div class="column2" align="justify"><h4>&#10004;Communication</h4><p>Mechanisms for defining call-ins and call-outs and the data marshalling associated with them</p></div>
  <div class="column2right" align="justify"><h4>&#10004;System primitives</h4><p>System primitives exposed by enclave runtime, such as thread and  memory management</p></div>
</div>
<div class="row2">
<div class="column2" align="justify"><h4>&#10004;Sealing</h4><p>Functions to support persistence of secrets</p></div>
  <div class="column2right" align="justify"><h4>&#10004;Attestation</h4><p>Functions to support verification of identity</p></div>
</div>
<div class="row2">
<div class="column2" align="justify"><h4>&#10004;Runtime and cryptographic libraries</h4><p>Pluggable libraries to provide the necessary language and cryptographic support within an enclave</p></div>
</div>
<hr/>

### New Features in Current Version
With release 0.4, we are excited to provide support for: 
* Operating System: Linux
* Trusted Execution Environments: Intel SGX 
* Runtime Libraries: C/C++ 
* Cryptographic Libraries: mBedTLS. 

Coming soon: Arm TrustZone support in Linux and both Intel SGX and TrustZone support in Windows!
