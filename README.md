# create GCP Cloud Build trigger
00 connect your GCP account with github repo
01 create the trigger to catch the event when having new `git tag push`

# push your deployment.yaml to a bucket
00 set the right docker image tag to deployment.yaml
01 upload it to a bucket
02 put the two in cloudbuild

# run trigger and add key for :kubectl to the cloudbuild machine when prompoted

# more note
view the git tag https://github.com/namgivu/k8s-tThao-helloword-demo/tags

view trigger                           https://console.cloud.google.com/cloud-build/triggers ?authuser=1&project=proud-lamp-289904
view trigger build progress and result https://console.cloud.google.com/cloud-build/builds   ?authuser=1&project=proud-lamp-289904

the storage bucket https://console.cloud.google.com/storage/browser/k8stthaohelloworddemo;tab=objects?authuser=1&project=proud-lamp-289904
.                  .                                                bucket name                       .          project id               
