# Chaos Engineering

## Exercices de chaos pour le cluster minikube dans le namespace monitoring

 ### Exercices pour le composant deployment/kube-prometheus-stack-grafana

| Exercice | Container | Lien | Commentaire
| ------ | ------ | ------ | ------ |
| [container-kill](documentation/experiments/container-kill.md) | grafana-sc-dashboard | [documentation/experiments/clusters/minikube/monitoring/container-kill-kube-prometheus-stack-grafana-grafana-sc-dashboard.md](PlDb) | |
| [container-kill](documentation/experiments/container-kill.md) | grafana | [documentation/experiments/clusters/minikube/monitoring/container-kill-kube-prometheus-stack-grafana-grafana.md](PlDb) | |
| [pod-delete](documentation/experiments/pod-delete.md) | grafana-sc-dashboard, grafana | [documentation/experiments/clusters/minikube/monitoring/pod-delete-kube-prometheus-stack-grafana.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | grafana-sc-dashboard | [documentation/experiments/clusters/minikube/monitoring/pod-cpu-hog-kube-prometheus-stack-grafana-grafana-sc-dashboard.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | grafana | [documentation/experiments/clusters/minikube/monitoring/pod-cpu-hog-kube-prometheus-stack-grafana-grafana.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | grafana-sc-dashboard | [documentation/experiments/clusters/minikube/monitoring/pod-mem-hog-kube-prometheus-stack-grafana-grafana-sc-dashboard.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | grafana | [documentation/experiments/clusters/minikube/monitoring/pod-mem-hog-kube-prometheus-stack-grafana-grafana.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | grafana-sc-dashboard | [documentation/experiments/clusters/minikube/monitoring/pod-io-stress-kube-prometheus-stack-grafana-grafana-sc-dashboard.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | grafana | [documentation/experiments/clusters/minikube/monitoring/pod-io-stress-kube-prometheus-stack-grafana-grafana.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | grafana-sc-dashboard | [documentation/experiments/clusters/minikube/monitoring/pod-network-corruption-kube-prometheus-stack-grafana-grafana-sc-dashboard.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | grafana | [documentation/experiments/clusters/minikube/monitoring/pod-network-corruption-kube-prometheus-stack-grafana-grafana.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | grafana-sc-dashboard | [documentation/experiments/clusters/minikube/monitoring/pod-network-duplication-kube-prometheus-stack-grafana-grafana-sc-dashboard.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | grafana | [documentation/experiments/clusters/minikube/monitoring/pod-network-duplication-kube-prometheus-stack-grafana-grafana.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | grafana-sc-dashboard | [documentation/experiments/clusters/minikube/monitoring/pod-network-loss-kube-prometheus-stack-grafana-grafana-sc-dashboard.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | grafana | [documentation/experiments/clusters/minikube/monitoring/pod-network-loss-kube-prometheus-stack-grafana-grafana.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | grafana-sc-dashboard | [documentation/experiments/clusters/minikube/monitoring/pod-network-latency-kube-prometheus-stack-grafana-grafana-sc-dashboard.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | grafana | [documentation/experiments/clusters/minikube/monitoring/pod-network-latency-kube-prometheus-stack-grafana-grafana.md](PlDb) | |

### Exercices pour le composant deployment/kube-prometheus-stack-kube-state-metrics

| Exercice | Container | Lien | Commentaire
| ------ | ------ | ------ | ------ |
| [container-kill](documentation/experiments/container-kill.md) | kube-state-metrics | [documentation/experiments/clusters/minikube/monitoring/container-kill-kube-prometheus-stack-kube-state-metrics-kube-state-metrics.md](PlDb) | |
| [pod-delete](documentation/experiments/pod-delete.md) | kube-state-metrics | [documentation/experiments/clusters/minikube/monitoring/pod-delete-kube-prometheus-stack-kube-state-metrics.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | kube-state-metrics | [documentation/experiments/clusters/minikube/monitoring/pod-cpu-hog-kube-prometheus-stack-kube-state-metrics-kube-state-metrics.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | kube-state-metrics | [documentation/experiments/clusters/minikube/monitoring/pod-mem-hog-kube-prometheus-stack-kube-state-metrics-kube-state-metrics.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | kube-state-metrics | [documentation/experiments/clusters/minikube/monitoring/pod-io-stress-kube-prometheus-stack-kube-state-metrics-kube-state-metrics.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | kube-state-metrics | [documentation/experiments/clusters/minikube/monitoring/pod-network-corruption-kube-prometheus-stack-kube-state-metrics-kube-state-metrics.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | kube-state-metrics | [documentation/experiments/clusters/minikube/monitoring/pod-network-duplication-kube-prometheus-stack-kube-state-metrics-kube-state-metrics.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | kube-state-metrics | [documentation/experiments/clusters/minikube/monitoring/pod-network-loss-kube-prometheus-stack-kube-state-metrics-kube-state-metrics.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | kube-state-metrics | [documentation/experiments/clusters/minikube/monitoring/pod-network-latency-kube-prometheus-stack-kube-state-metrics-kube-state-metrics.md](PlDb) | |

### Exercices pour le composant deployment/kube-prometheus-stack-operator

| Exercice | Container | Lien | Commentaire
| ------ | ------ | ------ | ------ |
| [container-kill](documentation/experiments/container-kill.md) | kube-prometheus-stack | [documentation/experiments/clusters/minikube/monitoring/container-kill-kube-prometheus-stack-operator-kube-prometheus-stack.md](PlDb) | |
| [pod-delete](documentation/experiments/pod-delete.md) | kube-prometheus-stack | [documentation/experiments/clusters/minikube/monitoring/pod-delete-kube-prometheus-stack-operator.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | kube-prometheus-stack | [documentation/experiments/clusters/minikube/monitoring/pod-cpu-hog-kube-prometheus-stack-operator-kube-prometheus-stack.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | kube-prometheus-stack | [documentation/experiments/clusters/minikube/monitoring/pod-mem-hog-kube-prometheus-stack-operator-kube-prometheus-stack.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | kube-prometheus-stack | [documentation/experiments/clusters/minikube/monitoring/pod-io-stress-kube-prometheus-stack-operator-kube-prometheus-stack.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | kube-prometheus-stack | [documentation/experiments/clusters/minikube/monitoring/pod-network-corruption-kube-prometheus-stack-operator-kube-prometheus-stack.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | kube-prometheus-stack | [documentation/experiments/clusters/minikube/monitoring/pod-network-duplication-kube-prometheus-stack-operator-kube-prometheus-stack.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | kube-prometheus-stack | [documentation/experiments/clusters/minikube/monitoring/pod-network-loss-kube-prometheus-stack-operator-kube-prometheus-stack.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | kube-prometheus-stack | [documentation/experiments/clusters/minikube/monitoring/pod-network-latency-kube-prometheus-stack-operator-kube-prometheus-stack.md](PlDb) | |

### Exercices pour le composant statefulset/alertmanager-kube-prometheus-stack-alertmanager

| Exercice | Container | Lien | Commentaire
| ------ | ------ | ------ | ------ |
| [container-kill](documentation/experiments/container-kill.md) | alertmanager | [documentation/experiments/clusters/minikube/monitoring/container-kill-alertmanager-kube-prometheus-stack-alertmanager-alertmanager.md](PlDb) | |
| [container-kill](documentation/experiments/container-kill.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/container-kill-alertmanager-kube-prometheus-stack-alertmanager-config-reloader.md](PlDb) | |
| [pod-delete](documentation/experiments/pod-delete.md) | alertmanager, config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-delete-alertmanager-kube-prometheus-stack-alertmanager.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | alertmanager | [documentation/experiments/clusters/minikube/monitoring/pod-cpu-hog-alertmanager-kube-prometheus-stack-alertmanager-alertmanager.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-cpu-hog-alertmanager-kube-prometheus-stack-alertmanager-config-reloader.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | alertmanager | [documentation/experiments/clusters/minikube/monitoring/pod-mem-hog-alertmanager-kube-prometheus-stack-alertmanager-alertmanager.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-mem-hog-alertmanager-kube-prometheus-stack-alertmanager-config-reloader.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | alertmanager | [documentation/experiments/clusters/minikube/monitoring/pod-io-stress-alertmanager-kube-prometheus-stack-alertmanager-alertmanager.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-io-stress-alertmanager-kube-prometheus-stack-alertmanager-config-reloader.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | alertmanager | [documentation/experiments/clusters/minikube/monitoring/pod-network-corruption-alertmanager-kube-prometheus-stack-alertmanager-alertmanager.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-network-corruption-alertmanager-kube-prometheus-stack-alertmanager-config-reloader.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | alertmanager | [documentation/experiments/clusters/minikube/monitoring/pod-network-duplication-alertmanager-kube-prometheus-stack-alertmanager-alertmanager.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-network-duplication-alertmanager-kube-prometheus-stack-alertmanager-config-reloader.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | alertmanager | [documentation/experiments/clusters/minikube/monitoring/pod-network-loss-alertmanager-kube-prometheus-stack-alertmanager-alertmanager.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-network-loss-alertmanager-kube-prometheus-stack-alertmanager-config-reloader.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | alertmanager | [documentation/experiments/clusters/minikube/monitoring/pod-network-latency-alertmanager-kube-prometheus-stack-alertmanager-alertmanager.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-network-latency-alertmanager-kube-prometheus-stack-alertmanager-config-reloader.md](PlDb) | |

### Exercices pour le composant statefulset/prometheus-kube-prometheus-stack-prometheus

| Exercice | Container | Lien | Commentaire
| ------ | ------ | ------ | ------ |
| [container-kill](documentation/experiments/container-kill.md) | prometheus | [documentation/experiments/clusters/minikube/monitoring/container-kill-prometheus-kube-prometheus-stack-prometheus-prometheus.md](PlDb) | |
| [container-kill](documentation/experiments/container-kill.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/container-kill-prometheus-kube-prometheus-stack-prometheus-config-reloader.md](PlDb) | |
| [pod-delete](documentation/experiments/pod-delete.md) | prometheus, config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-delete-prometheus-kube-prometheus-stack-prometheus.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | prometheus | [documentation/experiments/clusters/minikube/monitoring/pod-cpu-hog-prometheus-kube-prometheus-stack-prometheus-prometheus.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-cpu-hog-prometheus-kube-prometheus-stack-prometheus-config-reloader.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | prometheus | [documentation/experiments/clusters/minikube/monitoring/pod-mem-hog-prometheus-kube-prometheus-stack-prometheus-prometheus.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-mem-hog-prometheus-kube-prometheus-stack-prometheus-config-reloader.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | prometheus | [documentation/experiments/clusters/minikube/monitoring/pod-io-stress-prometheus-kube-prometheus-stack-prometheus-prometheus.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-io-stress-prometheus-kube-prometheus-stack-prometheus-config-reloader.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | prometheus | [documentation/experiments/clusters/minikube/monitoring/pod-network-corruption-prometheus-kube-prometheus-stack-prometheus-prometheus.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-network-corruption-prometheus-kube-prometheus-stack-prometheus-config-reloader.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | prometheus | [documentation/experiments/clusters/minikube/monitoring/pod-network-duplication-prometheus-kube-prometheus-stack-prometheus-prometheus.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-network-duplication-prometheus-kube-prometheus-stack-prometheus-config-reloader.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | prometheus | [documentation/experiments/clusters/minikube/monitoring/pod-network-loss-prometheus-kube-prometheus-stack-prometheus-prometheus.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-network-loss-prometheus-kube-prometheus-stack-prometheus-config-reloader.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | prometheus | [documentation/experiments/clusters/minikube/monitoring/pod-network-latency-prometheus-kube-prometheus-stack-prometheus-prometheus.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | config-reloader | [documentation/experiments/clusters/minikube/monitoring/pod-network-latency-prometheus-kube-prometheus-stack-prometheus-config-reloader.md](PlDb) | |

