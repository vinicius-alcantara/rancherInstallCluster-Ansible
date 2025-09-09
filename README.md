# rancherInstallCluster-Ansible

Automação via Ansible para instalação e configuração de **Rancher** via RKE.

---

##  Descrição

Este projeto provê uma solução automatizada (Infrastructure as Code) usando Ansible para instalar e configurar um **cluster Kubernetes gerenciado pelo Rancher**. Ele simplifica tarefas como provisão de nós, instalação do Rancher via RKE, configuração de TLS, controle de versão e mais.

---

##  Estrutura Recomendada (Exemplo)

```text
rancherInstallCluster-Ansible/
├── inventory/
│   ├── hosts.ini
│   └── group_vars/
│       └── all.yml
├── roles/
│   ├── prerequisites/
│   ├── kubernetes/
│   └── rancher/
├── playbook.yml
├── requirements.yml
└── README.md
