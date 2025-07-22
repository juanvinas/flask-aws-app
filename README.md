# flask-aws-app
lab com AWS
# 🚀 Deploy Automático de App Flask na AWS EC2 com GitHub Actions

Este projeto é um exemplo simples de uma aplicação Flask com deploy automático usando GitHub Actions em uma instância EC2 (Ubuntu).

---

## 🔧 Pré-requisitos

- Conta AWS com instância EC2 (Ubuntu)
- GitHub repository
- Chave SSH da instância configurada no GitHub como Secret (`EC2_SSH_KEY`)
- IP público da instância EC2
- Python 3 instalado na EC2

---

## 📦 Tecnologias usadas

- Python 3 / Flask
- GitHub Actions
- SSH + systemd
- UFW (firewall)
- EC2 (Ubuntu Server)

---

## 📁 Instalação local

```bash
git clone git@github.com:seu-usuario/meu_site.git
cd meu_site
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py
