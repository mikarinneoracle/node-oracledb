## OCI DevOps Docker  build for NodeJS with ATP instance created via OSOK

Build pipeline required parameters: 
<ul>
<li><b>password</b> e.g. <i>WelcomeFolks123#!</i></li>
<li><b>instant_client</b> e.g. <i>instantclient-basic-linux.x64-21.7.0.0.0dbru.zip</i> from object storage PAR. Download the file from OTN https://download.oracle.com/otn_software/linux/instantclient/217000/instantclient-basic-linux.x64-21.7.0.0.0dbru.zip to it.
</ul>

In build_spec.yaml adjust compartment and other OCIDs including the  OKE endpoint and the OCIR login with OCI Vault 
(create a <b>secret</b> for <i>Docker login password</i>)

