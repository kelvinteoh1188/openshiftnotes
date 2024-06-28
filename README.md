class room note
apiVersion: v1
kind: Pod
metadata:
  labels:
    run: myubi
  name: mypod
spec:
  containers:
  - image: quay.io/kelvinlai/myweb:openshift
    name: mycontainer
