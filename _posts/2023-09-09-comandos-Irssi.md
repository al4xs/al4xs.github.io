---
title: Tutorial de comandos IRC para chat IRSSI
date: 2023-09-09 20:43:00 +0800
categories: [irc]
tags: [irc, portal, comunicacao, comandos] # TAG names should always be lowercase
image:
    path: /assets/img/posts/irc-robot.png
---

Este é um guia, um tutorial completo pros amantes do IRC, em especial, pra quem gosta de usar o IRC pelo terminal com IRSSI.

## SUMÁRIO

- [ Comandos de Configuração](#comandos-de-configuração)
- [ Comandos de Chat](#comandos-de-chat)
- [ Comandos mais utilizados](#comandos-mais-utilizados)
- [ IRSSI na rede TOR](#irssi-na-rede-toronion)


# COMANDOS DE CONFIGURAÇÃO

### Regitrar apelido no IRC com seu email

```
/msg NickServ REGISTER password [email]
Você receberá um código no e-mail para confirmar
```

### Se identificar no IRC com sua senha para seu apelido

```
/msg NickServ IDENTIFY password
```

### Cria uma nova senha para seu apelido

```
/msg NickServ SET PASSWORD new-password
```

### Mostra seu e-mail para seu apelido

```
/msg NickServ SET EMAIL address
```

### Esconde info do apelido

```
/msg NickServ SET HIDE {EMAIL | STATUS | USERMASK | QUIT} {ON | OFF}
```

### Desconecta pessoas que tentarem usar seu apelido automaticamente em 1 minuto

```
/msg NickServ SET KILL {ON | QUICK | IMMED | OFF}
```

### Obriga os servidores se comunicarem com você só por mensagem

```
/msg NickServ SET MSG {ON | OFF}
```

### Envia sua senha pro seu email caso você esqueça

```
 /msg NickServ SENDPASS nickname
```

### Auto-Conectar

```
/network add -autosendcmd "/msg nickserv identify senha; wait 400" freenode
```

---

# Comandos de CHAT

### fazer a mensagem brilhar para um usuario (todos veem)

```
nomedousuario: eaeeee to aqui!
```

### Abrir janela privada com usuario selecionado (So o usuario ve)

```
/query nomedousuario
```

### Mandar msg pro usuario de forma privada

```
/msg nomedousuario eaae mano, tudo bem?
```

---

# Comandos mais utilizados

/away fui no banheiro `comando pra mostrar que voce esta off`

/back `sair do modo away`

/j #canal `abrir canal`

/window close `fechar janela atual (em alguns modos só funciona /close)`

/leave `deixar sala`

/server list `lista servidores disponíveis para se conectar`

/part `sair`

/win list `listar canais que entrou`

/win number `navegar entre os canais`

alt + num `navegar entre os canais`

/msg usuário Hello friend! `mandar msg priv`

/ban `banir usuário`

/kick `chutar um usuário`

/topic `mostrar ou editar tópicos`

/window close `forçar fechar janela`

/exit `sair`

/server list `ver a lista de servidores configurados`

/names `lista nomes de usuários de um canal`

/me esta cansado! `mostra seu humor`

/dcc send [nick] [arquivo] `Manda o arquivo especificado para o nick especificado`

---

# IRSSI na rede TOR(.onion)

> E se você gostou de ler até aqui, você também vai gostar de usar o IRC na rede tor que te proporciona, anonimato e privacidade.
{: .prompt-info }

[**Como usar o IRSSI na rede TOR - Clique AQUI**](/posts/fale-comigo-canal-irc/)
