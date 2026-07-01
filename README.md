
# Testes Automatizados

- Testes, Build, Deploy e Profissionais Envolvidos

## Build e Deploy

- Build = Compilação da aplicação gerando arquivos que podem ser enviados para produção.

- Deploy = Colocar a aplicação em um ambiente e produção/implantar.

## Testes Automatizados 

- Uma etapa do Build. A app precisar passar nos testes para que o build seja concluído e o 
deploy seja feito.

## Desenvolvedor ou Analista de Testes

- Geralmente programa os testes unitários e de integração para liberar o Build.

## QA ( Quality Assurance) Analista de Qualidade

- Realiza vários outros tipos de testes e observa aspectos de qualidade e seguranca
da aplicação.

- Utiliza outros softwares para verificar qualidade e confiabilidade da aplicação desenvolvida em relação em reusitos.

---

# Overview

## Introdução a Testes de softwares

- Testes Automatizados são diferentes de testes por observações. Trata-se de pré-programar
o sistema para identificar flhas, bugs e erros automaticamente, antes da implementacao da app.

## O que devo testar

- Testar exaustivamente tudo ou quase tudo, mas testar tudo é impraticável, então o que realmente devo testar? Sempre devemos testar todos os casos de usos ou as funcionalidades mais criticas. Definir um % de cobertura de testes

## Níveis de Testes

- Testes unitários / Testes de Unidade: Testar a menor parte de um codigo = um metodo. Simples, facil e direto.

- Testes de Integracao: Não tem nada a ver com integração com BD ou com outros sistemas. Sao testes em caso em q.....
Proibido conectar no banco e/ou sair da rede.

---

# Ferramentas e Locais dos Testes

## JUNIT + MOCKITO

- JUNIT: Framework de testesautimatizados para Java.
- MOCKITO: É uma biblioteca para simular/mocar dados;

## JACOCO

- Verificação de cobertura de testes(%)

## Dependencia no POM

```bash
  <dependecia>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-test</artifactId>
    <scope>test</scope>
  </dependecia>
```

# Na Pratica

## Teste uniatioc com JUNIT

- Primeiramente deve localizar a pasta test no seu projeto  e la criar uma pasta com o nome da classe que ira trabalhar.

![image alt](https://github.com/DouglasESilva/Testes-Automatizados/blob/f1f271a21f62051158a5c22d499f83003a7b301c/Captura%20de%20tela%202026-07-01%20135711.png)

- A classe na pasta de test deve ter o mesmo nome das classe ja criada. Tendo uma pequena diferencia onde voce deve adicionar a palavra Test ao fina do nome da classe.

## Aqui esta um exemplo de teste unitario.

