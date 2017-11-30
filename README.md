# cheatsheet-kubernetes-A4
Kubernetes CheatSheets In A4

<a href="https://github.com/DennyZhang?tab=followers"><img align="right" width="200" height="183" src="https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/fork_github.png" /></a>

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

[![LinkedIn](https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/linkedin.png)](https://www.linkedin.com/in/dennyzhang001) <a href="https://www.dennyzhang.com/slack" target="_blank" rel="nofollow"><img src="http://slack.dennyzhang.com/badge.svg" alt="slack"/></a> [![Github](https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/github.png)](https://github.com/DennyZhang)

File me [tickets](https://github.com/DennyZhang/cheatsheet-kubernetes-A4/issues) or star [the repo](https://github.com/DennyZhang/cheatsheet-kubernetes-A4).

Printable version on A4 page: [cheatsheet-kubernetes-A4.pdf](cheatsheet-kubernetes-A4.pdf)

<a href="https://www.dennyzhang.com"><img align="right" width="185" height="37" src="https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/dns_small.png"></a>

See more CheatSheets from Denny: [here](https://github.com/topics/denny-cheatsheets)

- Commands

| Name                                        | Summary                    |
| :------------------------------------------ | ---------------------      |
| `kubectl get services`                      | List all services          |
| `kubectl get pods`                          | List all pods              |
| `kubectl get pods -o wide`                  | List all pods with details |
| `kubectl delete pod hello-node-95913-n63qs` |                            |
| `kubectl get nodes`                         | like `docker ps`           |
| `kubectl describe pod nginx-app-413181-cn`  | like `docker inspect`      |
| `kubectl logs`                              | like `docker logs`         |
| `kubectl exec`                              | like `docker exec`         |
| `kubectl get events`                        | View cluster events        |
| `kubectl get deploy`                        |                            |

- System

| Name                   | Summary             |
| :--------------------- | ---------           |
| `kubectl version`      | Get kubectl version |
| `kubectl cluster-info` |                     |
| `kubectl config view`  | Get configuration   |

- Scale

| Name                                              | Summary   |
| :-----------------------------------------------  | --------- |
| `kubectl scale --replicas=3 deployment/nginx-app` |           |

- Upgrade  

| Name                                                  | Summary                |
| :---------------------------------------------------- | ---------------------- |
| `kubectl rolling-update app-v1 app-v2 --image=img:v2` | online rolling upgrade |
| `kubectl rolling-update app-v1 app-v2 --rollback`     |                        |
| `kubectl rollout status deployment/nginx-app`         |                        |
| `kubectl rollout history deployment/nginx-app`        |                        |

# Related Resources
- https://github.com/alex1x/kubernetes-cheatsheet

<a href="https://www.dennyzhang.com"><img align="right" width="201" height="268" src="https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/denny_201706.png"></a>

<a href="https://www.dennyzhang.com"><img align="right" src="https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/dns_small.png"></a>

# License
- Code is licensed under [MIT License](https://www.dennyzhang.com/wp-content/mit_license.txt).
