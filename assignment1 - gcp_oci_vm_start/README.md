<h1>VM Lifecycle on GCP and OCI — Tutorial</h1>
<h2>Video:</h2>
<ul><li>Oracle Cloud + Google Cloud Tutorial: ["Link"](https://drive.google.com/file/d/155QlspxIFk-pXRzhwrNSo4GSHYb0h906/view?usp=sharing)</li></ul>
<h2>Google Cloud (GCP)</h2>
<h3>Creation</h3>
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