# Security policy

We take the security of OneTrace.pro and of our open-source libraries and plugins seriously, and we appreciate responsible disclosure.

## Reporting a vulnerability

**Please do not open a public issue.** Email [support@onetrace.pro](mailto:support@onetrace.pro) with the subject starting with **Security**, and include:

- the affected product: the platform (`cdp.onetrace.pro` or a white-label domain), the tracker, or a repository and its version;
- a description of the issue and its impact;
- steps to reproduce or a proof of concept;
- how you would like to be credited, if at all.

We acknowledge reports within two business days, keep you updated while we work on a fix, and let you know when it is released. Please give us reasonable time to fix the issue before disclosing it publicly.

## Scope

- The OneTrace.pro platform, its public API and the JavaScript tracker
- The libraries and plugins in this organization: [onetrace-php](https://github.com/OneTracePro/onetrace-php), [onetrace-laravel](https://github.com/OneTracePro/onetrace-laravel), [onetrace-woocommerce](https://github.com/OneTracePro/onetrace-woocommerce), [onetrace-magento2](https://github.com/OneTracePro/onetrace-magento2)

When testing the platform, use only your own project and accounts, do not access other customers' data, and avoid anything that degrades the service: no denial of service, load testing, spam or social engineering.

## Supported versions

Security fixes go into the latest minor release of each library and plugin. Please update to it before reporting.
