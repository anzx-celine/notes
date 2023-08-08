1. Create service account & secret as well as necessary bindings for the new bot in [xplore-infra](https://github.com/anzx/xplore-infra/tree/master/terraform/common)
2. upload secreat (json format)
  > to verify the secret is added correctly, you have to impersonate a service account to be able to view the secrets
3. Setup deployment in [xplore-cloud-functions](https://github.com/anzx/xplore-cloud-functions/blob/master/common.libsonnet)
4. add trigger (no longer in k8s)
5. add notification after prod deployment
