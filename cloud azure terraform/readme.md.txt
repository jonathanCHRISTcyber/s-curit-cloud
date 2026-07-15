« J'ai d'abord déployé l'infrastructure manuellement sur Azure pour comprendre les concepts réseau et sécurité, puis j'ai automatisée avec Térraform en Infrastructure as Code. »

azure-secure-infrastructure/
│
├── terraform/
│   ├── provider.tf
│   ├── main.tf
│   ├── variables.tf
│   ├── outputs.tf
│   ├── terraform.tfvars
│   ├── networking.tf
│   ├── security.tf
│   ├── compute.tf
│   └── versions.tf
│
├── scripts/
│   ├── install-nginx.sh
│   ├── install-fail2ban.sh
│   └── install-ufw.sh
│
├── docs/
│   ├── deployment.md
│   ├── networking.md
│   ├── security.md
│   └── terraform.md
│
├── screenshots/
│
└── README.md