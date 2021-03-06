## Kabanero Foundation Components
| Namespace | Pod | Container | CPU Requests | CPU Limits | Memory Requests | Memory Limits |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| istio-system | cluster-local-gateway-7795cc7956-lt7rf | | | | | |
| | | istio-proxy | 10m |  |  |  |
| istio-system | istio-citadel-f88bdd688-2nx7d | | | | | |
| | | citadel | 10m |  |  |  |
| istio-system | istio-galley-f8f96c6bf-scjjb | | | | | |
| | | galley | 10m |  |  |  |
| istio-system | istio-ingressgateway-65bf84457c-9xs8t | | | | | |
| | | istio-proxy | 100m | 2 | 128Mi | 1Gi |
| istio-system | istio-pilot-6955f55cbc-zvzjw | | | | | |
| | | discovery | 500m |  | 2Gi |  |
| kabanero | che-operator-b99c789b-s2nds | | | | | |
| | | che-operator |  |  |  |  |
| kabanero | kabanero-cli-5cc54f6d7f-kfzrz | | | | | |
| | | kabanero-cli |  |  |  |  |
| kabanero | kabanero-landing-5fb9f667b6-t8mds | | | | | |
| | | kabanero-landing |  |  |  |  |
| kabanero | kabanero-operator-6bdfc77bd4-g6dxv | | | | | |
| | | kabanero-operator |  |  |  |  |
| knative-eventing | eventing-controller-758d785bf7-wtkjk | | | | | |
| | | eventing-controller |  |  |  |  |
| knative-eventing | eventing-webhook-7ff46cd45f-dvrmg | | | | | |
| | | eventing-webhook |  |  |  |  |
| knative-eventing | imc-controller-75d7f598df-5rng5 | | | | | |
| | | controller |  |  |  |  |
| knative-eventing | imc-dispatcher-77f565585c-9mvvb | | | | | |
| | | dispatcher |  |  |  |  |
| knative-eventing | in-memory-channel-controller-6b4967d97b-56f57 | | | | | |
| | | controller |  |  |  |  |
| knative-eventing | in-memory-channel-dispatcher-8bbcd4f9-n2xbh | | | | | |
| | | dispatcher |  |  |  |  |
| knative-eventing | sources-controller-788874d5fc-zrcwb | | | | | |
| | | controller | 100m |  | 100Mi |  |
| knative-serving | activator-7dbd64d896-8wsgh | | | | | |
| | | activator | 300m | 1 | 60Mi | 600Mi |
| knative-serving | autoscaler-6c9d77cc94-9j8wf | | | | | |
| | | autoscaler | 30m | 300m | 40Mi | 400Mi |
| knative-serving | autoscaler-hpa-7d7c8c6676-pkqn7 | | | | | |
| | | autoscaler-hpa | 100m | 1 | 100Mi | 1000Mi |
| knative-serving | controller-7f45cd9dc5-dpwwf | | | | | |
| | | controller | 100m | 1 | 100Mi | 1000Mi |
| knative-serving | networking-istio-7f6674695f-fhrqp | | | | | |
| | | networking-istio | 100m | 1 | 100Mi | 1000Mi |
| knative-serving | webhook-6b8bfb8c46-dvq78 | | | | | |
| | | webhook | 20m | 200m | 20Mi | 200Mi |
| knative-sources | github-controller-manager-0 | | | | | |
| | | manager | 100m | 1 | 100Mi | 1000Mi |
| openshift-operators | appsody-operator-5d7dd89467-54rz2 | | | | | |
| | | appsody-operator |  |  |  |  |
| openshift-operators | elasticsearch-operator-5d4b85bcf8-bzscl | | | | | |
| | | elasticsearch-operator |  |  |  |  |
| openshift-operators | istio-node-4dvcb | | | | | |
| | | install-cni | 100m | 500m | 100Mi | 100Mi |
| openshift-operators | istio-node-f9jtp | | | | | |
| | | install-cni | 100m | 500m | 100Mi | 100Mi |
| openshift-operators | istio-node-jj4bd | | | | | |
| | | install-cni | 100m | 500m | 100Mi | 100Mi |
| openshift-operators | istio-node-jr8vq | | | | | |
| | | install-cni | 100m | 500m | 100Mi | 100Mi |
| openshift-operators | istio-node-t8trh | | | | | |
| | | install-cni | 100m | 500m | 100Mi | 100Mi |
| openshift-operators | istio-node-w594p | | | | | |
| | | install-cni | 100m | 500m | 100Mi | 100Mi |
| openshift-operators | istio-operator-755cc98b8c-gbf2x | | | | | |
| | | istio-operator |  |  |  |  |
| openshift-operators | jaeger-operator-55f47cccbc-j54ll | | | | | |
| | | jaeger-operator |  |  |  |  |
| openshift-operators | kiali-operator2-75995c7479-xqft9 | | | | | |
| | | operator |  |  |  |  |
| openshift-operators | knative-eventing-operator-56b75948c5-8992b | | | | | |
| | | knative-eventing-operator |  |  |  |  |
| openshift-operators | knative-openshift-ingress-c9c677ff7-82mgs | | | | | |
| | | knative-openshift-ingress |  |  |  |  |
| openshift-operators | knative-serving-operator-5d4d86f85c-grfmq | | | | | |
| | | knative-serving-operator |  |  |  |  |
| openshift-operators | openshift-pipelines-operator-75d79846c5-pt9x7 | | | | | |
| | | openshift-pipelines-operator |  |  |  |  |
| tekton-pipelines | tekton-dashboard-7b49b5b547-9pp8j | | | | | |
| | | oauth-proxy |  |  |  |  |
| | | tekton-dashboard |  |  |  |  |
| tekton-pipelines | webhooks-extension-6579c6f49b-7ljlg | | | | | |
| | | webhooks-extension |  |  |  |  |
