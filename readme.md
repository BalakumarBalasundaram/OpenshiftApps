# Installation

https://access.redhat.com/documentation/en-us/red_hat_openshift_local/2.5/html/getting_started_guide/introducing_gsg

# Usage

https://access.redhat.com/documentation/en-us/red_hat_openshift_local/2.5/html/getting_started_guide/using_gsg

# web Console
The server is accessible via web console at:
  https://console-openshift-console.apps-crc.testing

Log in as administrator:
  Username: kubeadmin
  Password: 2PIer-EryXn-ISI8X-cKyh9

Log in as user:
  Username: developer
  Password: developer

Use the 'oc' command line interface:
  PS> & crc oc-env | Invoke-Expression
  PS> oc login -u developer https://api.crc.testing:6443
