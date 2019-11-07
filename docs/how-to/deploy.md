# How to deploy

Deployment to production environment is done by CircleCI and is triggered
by git tag creation.

Staging environment is deployed on every tag creation or push to master/release
branch.

In case you need to manually deploy for whatever reason use following command:

    AWS_PROFILE=... ENV=... VERSION=... make deploy