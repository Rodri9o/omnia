Best Practices
==============

* Ensure that PowerCap policy is disabled and the BIOS system profile is set to 'Performance' on the Control Plane.
* Ensure that there is at least 50% (~35%)free space on the Control Plane before running Omnia.
* Disable SElinux on the Control Plane.
* Use a `PXE mapping file <samplefiles.html>`_  even when using DHCP configuration to ensure that IP assignments remain persistent across Control Plane reboots.
* Avoid rebooting the Control Plane as much as possible to ensure that all network configuration does not get disturbed.
* Review the prerequisites before running Omnia Scripts.
* Ensure that the firefox version being used on the control plane is the latest available. This can be achieved using ``dnf update firefox -y``
* It is recommended to configure devices using Omnia playbooks for better interoperability and ease of access.