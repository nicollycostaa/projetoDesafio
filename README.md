# 🚀 ProjetoDesafio

Este projeto é um exercício prático para implantar uma aplicação web simples em um cluster Kubernetes.

## 📋 Índice

- Instalação
- Uso
- Contribuição
- Licença

## 🛠️ Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/projetoDesafio.git
- Navegue até o diretório do projeto:
    ```bash
    cd projetoDesafio
- Instale as dependências (se houver):
    ```bash
    npm install

## 🚀 Uso
- Aplique o arquivo pod-desafio.yaml para criar o Deployment:
    ```bash
    kubectl apply -f pod-desafio.yaml
- Aplique o arquivo service.yaml para criar o Service:
    ```bash
    kubectl apply -f service.yaml
- Verifique se os pods estão em execução:
    ```bash
    kubectl get pods
- Verifique o Service e obtenha o endereço IP e a porta:
    ```bash
    kubectl get svc
- Acesse a aplicação web através do endereço IP e porta fornecidos pelo Service.

## 🤝 Contribuição
-  Faça um fork do projeto.
- Crie uma nova branch:
    ```bash
    git checkout -b minha-nova-feature
- Faça suas alterações e commit:
    ```bash
    git commit -m 'Adiciona nova feature'
- Envie para o branch original:
    ```bash
    git push origin minha-nova-feature
- Crie um Pull Request.

## 📄 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
- Feito com ❤️ por Nicolly Costa.