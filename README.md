# 📘 Ansible Basics – Variables, Conditions & Data Types

A beginner-friendly project that demonstrates core Ansible concepts through simple and clear YAML examples. Ideal for learning and revising the building blocks of Ansible automation.

---

## 🧠 What You'll Learn

- 📌 How to define and use **variables** (scalars, dictionaries, lists)
- ⚙️ Use of **conditionals** (when statements)
- 🔍 Basic **data types** in Ansible YAML
- 🧩 Jinja2 templating basics (where applicable)

---

## 📁 Structure

ansible-basics/
├── playbook.yml
├── inventory.ini
└── vars/
└── vars.yml


---

## 🛠️ Tech Stack

- 🧾 Ansible
- ⚙️ YAML
- 🐧 Linux shell (target machine)

---

## ▶️ How to Run

### 🔧 Prerequisites

- Ansible installed (`ansible --version`)
- An inventory file with at least one accessible host

### 🧪 Run the Playbook

```bash
ansible-playbook -i inventory.ini playbook.yml
