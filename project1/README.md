# hicloud S3 Sample Codes

This repository intends to demonstrate how to perform several S3-compatible operations on **[hicloud S3](http://hicloud.hinet.net/hicloud_s3_about.html)** using AWS SDKs for various languages.

## Getting Started

### hicloud S3 Account and Credentials
To access hicloud S3, you will need to sign up for a hicloud S3 account.

To sign up for a hicloud S3 account
1.	Go to https://userportal.hicloud.hinet.net/cloud/
2.	Follow the on-screen instructions.

When you sign up, hicloud S3 provides you with security credentials that are specific to your account. Two of these credentials, your access key ID and your secret key, are used by the SDK whenever it accesses to hicloud S3. The security credentials authenticate requests to the service and identify you as the sender of a request. The following examples show these credentials.

-	Access Key ID Example: U0U03U5UQXdNREl4TkRFek5UZ3hNek0yTURZd09EWJ0
-	Secret Key Example: WW1NNU9XVTNOLFF34kRNMk5DRTVaV0ZrTVRjMFpEVTFOV1kxWkRZeFlUTT0

Your secret key must remain a secret that is known only by you and hicloud S3. Keep it confidential in order to protect your account. Store it securely in a safe place, and never email it. Do not share it outside your organization, even if an inquiry appears to come from hicloud S3.No one who legitimately represents hicloud S3 will ever ask you for your secret key.