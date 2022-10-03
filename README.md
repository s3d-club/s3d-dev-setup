# S3D Developer Setup Project
This project defines scripts and resources that setup our development
environments.

## Related Documents
Please read our [LICENSE][lice], [CONTRIBUTING][cont], [CODE-OF-CONDUCT][code],
and [CHANGES][chge] documents before working in this project and anytime they
are update.

## Overview
Our developer setup projects defines scripts and related resources that in our
opininated view produce a great development enviornment. We build our EC2
instances with this script so all our development tools are installed and
configured when we login for the first time.

This project is referenced from our `aws-ec2` project where the `user-data`
scripting for the `work` template includes reference to this script such that
when the user first logs into the instance the script defined here runs.

[chge]: ./CHANGES.md
[code]: ./CODE-OF-CONDUCT.md
[cont]: ./CONTRIBUTING.md
[lice]: ./LICENSE.md
