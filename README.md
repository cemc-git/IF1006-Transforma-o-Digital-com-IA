# Auxiliador de Anamnese Hospitalar

## Descrição

O **Auxiliador de Anamnese Hospitalar** é uma ferramenta baseada em inteligência artificial (IA) que apoia os residentes na coleta de informações durante a anamnese hospitalar. O objetivo do projeto é melhorar a precisão e a eficiência da coleta e repasse de informações durante o processo de anamnese, diminuindo erros e aumentando a confiança dos residentes. Ele é destinado a residentes e médicos que buscam otimizar o atendimento clínico.

## Início Rápido

Essas instruções fornecerão uma cópia do projeto instalada e funcionando na sua máquina local para fins de desenvolvimento e teste.

### Instalação

Um passo a passo para configurar o ambiente de desenvolvimento:

```bash
# Clone o repositório
git clone https://github.com/cemc-git/IF1006-Transforma-o-Digital-com-IA.git
cd src
```

```bash
# Instale todas as dependências
pip install openai
pip install chainlit
```

```bash
# Configure as variáveis de ambiente (se aplicável), crie um .env na diretório src/
OPENAI_ASSISTANT_ID=...
OPENAI_API_KEY=...
```

## Uso

Demonstrações de como usar o projeto:

```python
# Exemplo de execução da ferramenta de IA para suporte à anamnese
chainlit run app.py
```

## Funcionalidades

- IA para guiar o diagnóstico conforme a anamnese
- Geração automática de relatórios de anamnese

## Como Contribuir

Contribuições são sempre bem-vindas, veja como você pode ajudar:
1. Clone o repositório e crie sua branch a partir de `main`.
2. `git checkout -b minha-nova-feature`
3. Faça suas alterações e commit.
4. Envie para a branch.
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE.md](LICENSE) para detalhes.

## Créditos

- Carlos Eduardo Mendonça Clark (@cemc@cin.ufpe.br)

## FAQ

**Pergunta 1:** Como faço para configurar o ambiente?

**Resposta:** Siga as instruções de instalação e qualquer etapa de configuração adicional indicada acima.

## Estado do Projeto

Este projeto foi desenvolvido apenas para a cadeira IF 1006.

## Screenshots
### Tela inicial
![image](https://github.com/user-attachments/assets/791711d8-271d-4280-8650-c475abf67504)
### Utilizando Speech-to-Text
![image](https://github.com/user-attachments/assets/819b339b-3bd3-49ea-8cb4-baff96d269fc)
### Resultado encontrado utilizando o banco de dados
![image](https://github.com/user-attachments/assets/ca5e26ed-55f1-44a7-a446-5a286fb7fd6e)
