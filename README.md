# DevOps-toolbox

Repo structure:

- `.github/workflows/build-and-push.yml` — CI/CD workflow for building and pushing images.
- `images/k9s-toolbox/Dockerfile` — image for Kubernetes tools and `k9s`.
- `images/bigdata-toolbox/Dockerfile` — image for Kafka, Spark and Hadoop tooling.
- `images/cloud-core-toolbox/Dockerfile` — image for Terraform, Ansible and Azure CLI.

## Folder layout

```
devops-toolbox/ (Nazwa Repozytorium)
├── .github/workflows/
│   └── build-and-push.yml      # Jeden automatyczny pipeline CI/CD
├── images/
│   ├── k9s-toolbox/            # Twardy zestaw do K8s (Twój obecny przypadek)
│   │   └── Dockerfile
│   ├── bigdata-toolbox/        # Zestaw z Kafką, Sparkiem i Hadoopem
│   │   └── Dockerfile
│   └── cloud-core-toolbox/     # Czysty Terraform + Ansible + Azure CLI
│       └── Dockerfile
└── README.md
```
