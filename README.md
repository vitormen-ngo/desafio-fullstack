<img src="https://ngosolucoes.com.br/wp-content/uploads/2021/07/Logo_Solucoes.png" alt="NGO Soluções" style="width:150px;"/>

[![StackShare](http://img.shields.io/badge/tech-stack-0690fa.svg?style=flat)](https://stackshare.io/ngo-solucoes/opus#stack)

# Desafio para candidatos à vaga de Desenvolvedor Fullstack

**Seja bem-vindo ao desafio de desenvolvimento da NGO Soluções!** 

O objetivo deste desafio é avaliarmos o seu domínio em desenvolvimento de software. Queremos conhecer melhor como você se organiza, a utilização de boas práticas no código, criação e consumo de APIs Restfull, conhecimento dos frameworks e tecnologias utilizadas.

*Leia o documento atentamente até o final e em caso de dúvidas, entre em contato com nosso time.*

Esse desafio foi pensado para um desenvolvedor Fullstack, então sinta-se a vontade, e desafiado :yum:, para tentar fazê-lo por completo.

Um layout final bem elaborado será um diferencial, mas não é necessário se preocupar muito com essa parte. 

Mãos a obra! :keyboard: :computer_mouse: :desktop_computer:

# Contexto 

Em todo aplicativo comercial temos um controle dos profissinais envolvidos no processo sejam usuários, responsáveis, gerentes, administradores, operadores, etc. Por isso um ponto importante de qualquer aplicação é permitir designarmos estas funções ou seja categorizar em tipos estes profissionais.  Ex.: ProfissionalAna = Médica, José = Professor... 

Vamos criar então uma aplicação que nos permita consultar, criar e editar essas informações e manter essa relação entre o profissional e seu tipo.

## Modelo de dados 
### Tipo de profissional
```js
{
  "id": xxx,                  // ID 
  "descricao": "test",        // descricao do tipo *Obrigatório
  "situacao": true,           // situacao do cadastro *Obrigatório
  "atualizadoEm": "",         // data e hora ultima atualizacao *Obrigatório
  "criadoEm": ""              // data e hora de cadastro *Obrigatório
}
```

### Profissional
```js
{
    "id": xxx,                   // ID
    "nome": "teste",             // Nome do profisisonal *Obrigatório
    "telefone": "(xx) xxxx",     // Telefone
    "email": "a@a.com",          // Endereço de e-mail do profissional
    "tipoDeProfissional": xxx,   // Vinculo com o tipo de profissional *Obrigatório
    "situacao": true,            // Situação do cadastro *Obrigatório
    "atualizadoEm": "",          // Data e hora da última atualização *Obrigatório
    "criadoEm": ""               // Data e hora da de cadastro *Obrigatório
}
```

## Requisitos funcionais 
### Backend 
- A API deve seguir as boas práticas e padrões de implementação REST
- Os dados deve ser salvos em um banco de dados
- Prover documentação para API. (Sugestão OpenAPI/Swagger)
- Use **Node.js** 
- Use **Javascript ECMA**
- Use **MongoDB**.

### Frontend 
- Criar uma tela home com menu de acesso as funcionalidades
- Uma tela de listagem para cada uma das entidades
- Uma tela de cadastro para cada uma das entidades
- Implementar solução usando **ReactJS** ultima versão disponível
- Fique a vontade para utilizar bibliotecas de componentes de mercado ou criar os seus
- Utilize **Javascript ECMA**

## Diferencial
- Escrever os testes para o código e as APIs geradas
- Documentação clara do código. Código comentado sempre é bom!
- Boas mensagens de commit ajudam!

## Requisitos não funcionais 
- Um arquivo README.md com o resumo de escolhas por frameworks, bibliotecas, banco de dados e como executar seu projeto.

## Opcional - Requisitos avançados 	
Estes requisitos são opcionais no desafio, sinta-se a vontade para deixá-los de lado, a menos que seja solicitado que os cumpra!   
- Criar mecanismo completo de autenticação e autorização (authentication/authorization/etc.) , como OAuth.
- Criar mecanismo de log e auditoria (quando/como/quem etc.).
- Configuração Docker para build da imagem do projeto, docker compose para subir banco de dados com carga inicial necessaria (migrations, seeders).

# Pontos focais ao avaliar seu código
- Com certeza muito mais do que o desafio completo é avaliarmos suas competências e habilidades até o ponto em que chegou.
- Sabemos que nem todos temos o mesmo tempo disponível, então como dissemos fique a vontade para ir até onde conseguir ou solicitar mais tempo para o processo, transparência total.
- Sinta-se livre pra usar bibliotecas de código aberto se fizerem sentido, e lembre que avaliaremos sua capacidade de resolver problemas reais.
- Procuramos por código funcional e limpo
- Exemplos práticos de conhecimento em NodeJS e Javascript ECMA e suas APIs padrões
- Orientação a testes 

# FAQ :question:
> Como devo fazer a entrega do desafio?
- Envie o link do seu repositório de código particular para quem te fez a solicitação de execução desse desafio.

> Se eu tiver dúvidas?
- Entre em contato com nosso time que esta te apoiando no processo seletivo ou pelo rh@ngosolucoes.com.br.
