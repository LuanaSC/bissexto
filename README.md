# Aplicativo de Ano Bissexto

Este é um projeto de um aplicativo desenvolvido no MIT App Inventor que permite aos usuários verificar se um determinado ano é bissexto ou não. O aplicativo oferece uma interface simples e intuitiva onde o usuário pode inserir um ano e receber uma resposta imediata sobre a condição do ano inserido.

## Funcionalidades

- **Verificação de Ano Bissexto**: O aplicativo verifica se o ano inserido é bissexto e exibe uma mensagem indicando o resultado.
- **Interface Simples**: Interface amigável com entrada de dados fácil e resposta clara.
- **Feedback Imediato**: Resposta instantânea ao usuário após a inserção do ano.

## Tecnologias Utilizadas

- **MIT App Inventor**: Plataforma de desenvolvimento usada para criar o aplicativo.

## Capturas de Tela

*Insira aqui algumas capturas de tela do aplicativo para demonstrar a interface e a funcionalidade.*

## Como Usar

1. **Abrir o Aplicativo**: Inicie o aplicativo no seu dispositivo.
2. **Inserir o Ano**: Digite o ano que deseja verificar no campo de entrada.
3. **Verificar**: Clique no botão de verificação.
4. **Resultado**: Veja a mensagem exibida indicando se o ano é bissexto ou não.

## Lógica de Verificação de Ano Bissexto

O algoritmo utilizado para determinar se um ano é bissexto segue as seguintes regras:
1. Um ano é bissexto se for divisível por 4.
2. No entanto, se o ano for divisível por 100, ele não é bissexto, a menos que:
3. O ano também seja divisível por 400. Neste caso, ele é bissexto.

Em termos de pseudocódigo:
```
se (ano % 4 == 0) {
    se (ano % 100 == 0) {
        se (ano % 400 == 0) {
            ano é bissexto
        } senão {
            ano não é bissexto
        }
    } senão {
        ano é bissexto
    }
} senão {
    ano não é bissexto
}
```

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorias no projeto.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## Contato

Se você tiver alguma dúvida ou sugestão, entre em contato:

- **Email**: silvacorreialuana@gmail.com
- **GitHub**:LuanaSC [LuanaSC](https://github.com/LuanaSC)

---

Esperamos que este aplicativo seja útil e fácil de usar. Agradecemos por experimentar o Aplicativo de Ano Bissexto!
