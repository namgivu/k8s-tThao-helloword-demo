# create GCP Cloud Build trigger
00 connect your GCP account with github repo
01 create the trigger to catch the event when having new `git tag push`

# push your deployment.yaml to a bucket
00 set the right docker image tag to deployment.yaml
01 upload it to a bucket
02 put the two in cloudbuild

# run trigger and add key for :kubectl to the cloudbuild machine when prompoted
