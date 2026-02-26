# TF01 - TechNexus Soluções Digitais
**Disciplina:** Implantação de Sistemas | **Professor:** Alexandre Tavares

## Aluno
- **Nome:** Paulo Vinicius Bernardes 
- **RA:** 6324010

## Sobre o Projeto
Este projeto consiste na implantação de um servidor Web Nginx configurado com:
- **Virtual Host**: Direcionando o tráfego para a pasta do projeto.
- **Página 404 Personalizada**: Interface exclusiva para erros de navegação.
- **Logs de Acesso**: Registros detalhados de requisições.

## Estrutura de Pastas
- `/website`: Código fonte do site (HTML/CSS).
- `/nginx`: Arquivo `site.conf` de configuração do servidor.
- `/scripts`: Script `install.sh` para automação do deploy.

## Como Instalar
```bash
sudo bash scripts/install.sh
