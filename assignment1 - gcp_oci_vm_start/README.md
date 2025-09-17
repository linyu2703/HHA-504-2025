<h1>VM Lifecycle on GCP and OCI — Tutorial</h1>
<h2>Video:</h2>
<ul><li>Oracle Cloud + Google Cloud Tutorial: https://drive.google.com/file/d/155QlspxIFk-pXRzhwrNSo4GSHYb0h906/view?usp=sharing</li></ul>
<h2>Google Cloud (GCP)</h2>
<h3>GCP creating</h3>
<ol><li>Log in to your google cloud account</li>
<li>Create or select your project</li>
<li>Create vm instance</li>
<li>Name the vm instance</li>
<li>Select your region/zone: us-east4</li>
<li>Select "E2" under general purpose</li>
<li>Select "e2-micro (2 vCPU, 1 core, 1 GB memory)"</li>
<li>Change operating system and storage to "Ubuntu"</li>
<li>Boot disk: default minimal</li>
<li>Network: default VPC; ephemeral public IP</li></ol>
<h3>GCP running</h3>
<img src="/assignment1 - gcp_oci_vm_start/images/gcp_running.png">
<h3>GCP stopping</h3>
<img src="/assignment1 - gcp_oci_vm_start/images/gcp_stopping.png">
<h3>GCP terminating</h3>
<img src="/assignment1 - gcp_oci_vm_start/images/gcp_terminating.png">
<ul><li>Delete instance and verify no disks/IPs remain</li></ul>
<h2>Oracle Cloud (OCI)</h2>
<h3> OCI creating</h3>
<ol><li>Log in to your oracle cloud account</li>
<li>Create instance</li>
<li>Name the vm instance</li>
<li>Compartment: root</li>
<li>Networking: VCN with Internet Connectivity (defaults)</li>
<li>Change image to "Ubuntu" -> "Canonical Ubuntu 24.04 Minimal"</li>
<li>Make sure shape is "VM.Standard.E2.1.Micro"</li>
<li>Public IP: ephemeral</li>
<li>Boot volume: default minimal</li>
<li>Select your existing virtual cloud network or create a new virutal cloud network</li>
<li>No SSH key, unless you want it</li>
<li>Review and create</li></ol>
<h3>OCI running</h3>
<img src="/assignment1 - gcp_oci_vm_start/images/oci_running.png">
<h3>OCI stopping</h3>
<img src="/assignment1 - gcp_oci_vm_start/images/oci_stopping.png">
<h3>OCI terminating</h3>
<img src="/assignment1 - gcp_oci_vm_start/images/oci_terminating.png">
<ul><li>Terminate and delete boot volume; verify cleanup</li></ul>
<h2>Reflection</h2>
<h3>Similarities</h3>
<ul><li></li></ul>
<h3>Differences</h3>
<ul><li></li></ul>
<h3>Preference and Explaination</h3>
<p></p>