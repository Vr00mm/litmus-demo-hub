# Chaos Engineering

## Exercices de chaos pour le cluster minikube dans le namespace litmus

 ### Exercices pour le composant deployment/chaos-center-litmus-frontend

| Exercice | Container | Lien | Commentaire
| ------ | ------ | ------ | ------ |
| [container-kill](documentation/experiments/container-kill.md) | litmusportal-frontend | [documentation/experiments/clusters/minikube/litmus/container-kill-chaos-center-litmus-frontend-litmusportal-frontend.md](PlDb) | |
| [pod-delete](documentation/experiments/pod-delete.md) | litmusportal-frontend | [documentation/experiments/clusters/minikube/litmus/pod-delete-chaos-center-litmus-frontend.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | litmusportal-frontend | [documentation/experiments/clusters/minikube/litmus/pod-cpu-hog-chaos-center-litmus-frontend-litmusportal-frontend.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | litmusportal-frontend | [documentation/experiments/clusters/minikube/litmus/pod-mem-hog-chaos-center-litmus-frontend-litmusportal-frontend.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | litmusportal-frontend | [documentation/experiments/clusters/minikube/litmus/pod-io-stress-chaos-center-litmus-frontend-litmusportal-frontend.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | litmusportal-frontend | [documentation/experiments/clusters/minikube/litmus/pod-network-corruption-chaos-center-litmus-frontend-litmusportal-frontend.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | litmusportal-frontend | [documentation/experiments/clusters/minikube/litmus/pod-network-duplication-chaos-center-litmus-frontend-litmusportal-frontend.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | litmusportal-frontend | [documentation/experiments/clusters/minikube/litmus/pod-network-loss-chaos-center-litmus-frontend-litmusportal-frontend.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | litmusportal-frontend | [documentation/experiments/clusters/minikube/litmus/pod-network-latency-chaos-center-litmus-frontend-litmusportal-frontend.md](PlDb) | |

### Exercices pour le composant deployment/chaos-center-litmus-server

| Exercice | Container | Lien | Commentaire
| ------ | ------ | ------ | ------ |
| [container-kill](documentation/experiments/container-kill.md) | graphql-server | [documentation/experiments/clusters/minikube/litmus/container-kill-chaos-center-litmus-server-graphql-server.md](PlDb) | |
| [container-kill](documentation/experiments/container-kill.md) | auth-server | [documentation/experiments/clusters/minikube/litmus/container-kill-chaos-center-litmus-server-auth-server.md](PlDb) | |
| [pod-delete](documentation/experiments/pod-delete.md) | graphql-server, auth-server | [documentation/experiments/clusters/minikube/litmus/pod-delete-chaos-center-litmus-server.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | graphql-server | [documentation/experiments/clusters/minikube/litmus/pod-cpu-hog-chaos-center-litmus-server-graphql-server.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | auth-server | [documentation/experiments/clusters/minikube/litmus/pod-cpu-hog-chaos-center-litmus-server-auth-server.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | graphql-server | [documentation/experiments/clusters/minikube/litmus/pod-mem-hog-chaos-center-litmus-server-graphql-server.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | auth-server | [documentation/experiments/clusters/minikube/litmus/pod-mem-hog-chaos-center-litmus-server-auth-server.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | graphql-server | [documentation/experiments/clusters/minikube/litmus/pod-io-stress-chaos-center-litmus-server-graphql-server.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | auth-server | [documentation/experiments/clusters/minikube/litmus/pod-io-stress-chaos-center-litmus-server-auth-server.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | graphql-server | [documentation/experiments/clusters/minikube/litmus/pod-network-corruption-chaos-center-litmus-server-graphql-server.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | auth-server | [documentation/experiments/clusters/minikube/litmus/pod-network-corruption-chaos-center-litmus-server-auth-server.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | graphql-server | [documentation/experiments/clusters/minikube/litmus/pod-network-duplication-chaos-center-litmus-server-graphql-server.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | auth-server | [documentation/experiments/clusters/minikube/litmus/pod-network-duplication-chaos-center-litmus-server-auth-server.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | graphql-server | [documentation/experiments/clusters/minikube/litmus/pod-network-loss-chaos-center-litmus-server-graphql-server.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | auth-server | [documentation/experiments/clusters/minikube/litmus/pod-network-loss-chaos-center-litmus-server-auth-server.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | graphql-server | [documentation/experiments/clusters/minikube/litmus/pod-network-latency-chaos-center-litmus-server-graphql-server.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | auth-server | [documentation/experiments/clusters/minikube/litmus/pod-network-latency-chaos-center-litmus-server-auth-server.md](PlDb) | |

### Exercices pour le composant deployment/chaos-exporter

| Exercice | Container | Lien | Commentaire
| ------ | ------ | ------ | ------ |
| [container-kill](documentation/experiments/container-kill.md) | chaos-exporter | [documentation/experiments/clusters/minikube/litmus/container-kill-chaos-exporter-chaos-exporter.md](PlDb) | |
| [pod-delete](documentation/experiments/pod-delete.md) | chaos-exporter | [documentation/experiments/clusters/minikube/litmus/pod-delete-chaos-exporter.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | chaos-exporter | [documentation/experiments/clusters/minikube/litmus/pod-cpu-hog-chaos-exporter-chaos-exporter.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | chaos-exporter | [documentation/experiments/clusters/minikube/litmus/pod-mem-hog-chaos-exporter-chaos-exporter.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | chaos-exporter | [documentation/experiments/clusters/minikube/litmus/pod-io-stress-chaos-exporter-chaos-exporter.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | chaos-exporter | [documentation/experiments/clusters/minikube/litmus/pod-network-corruption-chaos-exporter-chaos-exporter.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | chaos-exporter | [documentation/experiments/clusters/minikube/litmus/pod-network-duplication-chaos-exporter-chaos-exporter.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | chaos-exporter | [documentation/experiments/clusters/minikube/litmus/pod-network-loss-chaos-exporter-chaos-exporter.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | chaos-exporter | [documentation/experiments/clusters/minikube/litmus/pod-network-latency-chaos-exporter-chaos-exporter.md](PlDb) | |

### Exercices pour le composant deployment/chaos-operator-ce

| Exercice | Container | Lien | Commentaire
| ------ | ------ | ------ | ------ |
| [container-kill](documentation/experiments/container-kill.md) | chaos-operator | [documentation/experiments/clusters/minikube/litmus/container-kill-chaos-operator-ce-chaos-operator.md](PlDb) | |
| [pod-delete](documentation/experiments/pod-delete.md) | chaos-operator | [documentation/experiments/clusters/minikube/litmus/pod-delete-chaos-operator-ce.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | chaos-operator | [documentation/experiments/clusters/minikube/litmus/pod-cpu-hog-chaos-operator-ce-chaos-operator.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | chaos-operator | [documentation/experiments/clusters/minikube/litmus/pod-mem-hog-chaos-operator-ce-chaos-operator.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | chaos-operator | [documentation/experiments/clusters/minikube/litmus/pod-io-stress-chaos-operator-ce-chaos-operator.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | chaos-operator | [documentation/experiments/clusters/minikube/litmus/pod-network-corruption-chaos-operator-ce-chaos-operator.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | chaos-operator | [documentation/experiments/clusters/minikube/litmus/pod-network-duplication-chaos-operator-ce-chaos-operator.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | chaos-operator | [documentation/experiments/clusters/minikube/litmus/pod-network-loss-chaos-operator-ce-chaos-operator.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | chaos-operator | [documentation/experiments/clusters/minikube/litmus/pod-network-latency-chaos-operator-ce-chaos-operator.md](PlDb) | |

### Exercices pour le composant deployment/event-tracker

| Exercice | Container | Lien | Commentaire
| ------ | ------ | ------ | ------ |
| [container-kill](documentation/experiments/container-kill.md) | litmus-event-tracker | [documentation/experiments/clusters/minikube/litmus/container-kill-event-tracker-litmus-event-tracker.md](PlDb) | |
| [pod-delete](documentation/experiments/pod-delete.md) | litmus-event-tracker | [documentation/experiments/clusters/minikube/litmus/pod-delete-event-tracker.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | litmus-event-tracker | [documentation/experiments/clusters/minikube/litmus/pod-cpu-hog-event-tracker-litmus-event-tracker.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | litmus-event-tracker | [documentation/experiments/clusters/minikube/litmus/pod-mem-hog-event-tracker-litmus-event-tracker.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | litmus-event-tracker | [documentation/experiments/clusters/minikube/litmus/pod-io-stress-event-tracker-litmus-event-tracker.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | litmus-event-tracker | [documentation/experiments/clusters/minikube/litmus/pod-network-corruption-event-tracker-litmus-event-tracker.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | litmus-event-tracker | [documentation/experiments/clusters/minikube/litmus/pod-network-duplication-event-tracker-litmus-event-tracker.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | litmus-event-tracker | [documentation/experiments/clusters/minikube/litmus/pod-network-loss-event-tracker-litmus-event-tracker.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | litmus-event-tracker | [documentation/experiments/clusters/minikube/litmus/pod-network-latency-event-tracker-litmus-event-tracker.md](PlDb) | |

### Exercices pour le composant deployment/subscriber

| Exercice | Container | Lien | Commentaire
| ------ | ------ | ------ | ------ |
| [container-kill](documentation/experiments/container-kill.md) | subscriber | [documentation/experiments/clusters/minikube/litmus/container-kill-subscriber-subscriber.md](PlDb) | |
| [pod-delete](documentation/experiments/pod-delete.md) | subscriber | [documentation/experiments/clusters/minikube/litmus/pod-delete-subscriber.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | subscriber | [documentation/experiments/clusters/minikube/litmus/pod-cpu-hog-subscriber-subscriber.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | subscriber | [documentation/experiments/clusters/minikube/litmus/pod-mem-hog-subscriber-subscriber.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | subscriber | [documentation/experiments/clusters/minikube/litmus/pod-io-stress-subscriber-subscriber.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | subscriber | [documentation/experiments/clusters/minikube/litmus/pod-network-corruption-subscriber-subscriber.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | subscriber | [documentation/experiments/clusters/minikube/litmus/pod-network-duplication-subscriber-subscriber.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | subscriber | [documentation/experiments/clusters/minikube/litmus/pod-network-loss-subscriber-subscriber.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | subscriber | [documentation/experiments/clusters/minikube/litmus/pod-network-latency-subscriber-subscriber.md](PlDb) | |

### Exercices pour le composant deployment/workflow-controller

| Exercice | Container | Lien | Commentaire
| ------ | ------ | ------ | ------ |
| [container-kill](documentation/experiments/container-kill.md) | workflow-controller | [documentation/experiments/clusters/minikube/litmus/container-kill-workflow-controller-workflow-controller.md](PlDb) | |
| [pod-delete](documentation/experiments/pod-delete.md) | workflow-controller | [documentation/experiments/clusters/minikube/litmus/pod-delete-workflow-controller.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | workflow-controller | [documentation/experiments/clusters/minikube/litmus/pod-cpu-hog-workflow-controller-workflow-controller.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | workflow-controller | [documentation/experiments/clusters/minikube/litmus/pod-mem-hog-workflow-controller-workflow-controller.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | workflow-controller | [documentation/experiments/clusters/minikube/litmus/pod-io-stress-workflow-controller-workflow-controller.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | workflow-controller | [documentation/experiments/clusters/minikube/litmus/pod-network-corruption-workflow-controller-workflow-controller.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | workflow-controller | [documentation/experiments/clusters/minikube/litmus/pod-network-duplication-workflow-controller-workflow-controller.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | workflow-controller | [documentation/experiments/clusters/minikube/litmus/pod-network-loss-workflow-controller-workflow-controller.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | workflow-controller | [documentation/experiments/clusters/minikube/litmus/pod-network-latency-workflow-controller-workflow-controller.md](PlDb) | |

### Exercices pour le composant statefulset/chaos-center-litmus-mongo

| Exercice | Container | Lien | Commentaire
| ------ | ------ | ------ | ------ |
| [container-kill](documentation/experiments/container-kill.md) | mongo | [documentation/experiments/clusters/minikube/litmus/container-kill-chaos-center-litmus-mongo-mongo.md](PlDb) | |
| [pod-delete](documentation/experiments/pod-delete.md) | mongo | [documentation/experiments/clusters/minikube/litmus/pod-delete-chaos-center-litmus-mongo.md](PlDb) | |
| [pod-cpu-hog](documentation/experiments/pod-cpu-hog.md) | mongo | [documentation/experiments/clusters/minikube/litmus/pod-cpu-hog-chaos-center-litmus-mongo-mongo.md](PlDb) | |
| [pod-mem-hog](documentation/experiments/pod-mem-hog.md) | mongo | [documentation/experiments/clusters/minikube/litmus/pod-mem-hog-chaos-center-litmus-mongo-mongo.md](PlDb) | |
| [pod-io-stress](documentation/experiments/pod-io-stress.md) | mongo | [documentation/experiments/clusters/minikube/litmus/pod-io-stress-chaos-center-litmus-mongo-mongo.md](PlDb) | |
| [pod-network-corruption](documentation/experiments/pod-network-corruption.md) | mongo | [documentation/experiments/clusters/minikube/litmus/pod-network-corruption-chaos-center-litmus-mongo-mongo.md](PlDb) | |
| [pod-network-duplication](documentation/experiments/pod-network-duplication.md) | mongo | [documentation/experiments/clusters/minikube/litmus/pod-network-duplication-chaos-center-litmus-mongo-mongo.md](PlDb) | |
| [pod-network-loss](documentation/experiments/pod-network-loss.md) | mongo | [documentation/experiments/clusters/minikube/litmus/pod-network-loss-chaos-center-litmus-mongo-mongo.md](PlDb) | |
| [pod-network-latency](documentation/experiments/pod-network-latency.md) | mongo | [documentation/experiments/clusters/minikube/litmus/pod-network-latency-chaos-center-litmus-mongo-mongo.md](PlDb) | |

