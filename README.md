# Trabalho 1 - Aplicação Android Hello World

**Disciplina:** Desenvolvimento de Aplicações Móveis (DAM)
**Aluno:** Martim Machado Ramos A51736
**Data:** 7 de março de 2026
**URL do Repositório:** https://github.com/martimramos32/Hello_World_V2_App

## 1. Introdução
Este projeto é uma introdução ao Android Studio. O objetivo foi criar uma aplicação de telemóvel simples, perceber onde ficam guardados os ficheiros e aprender a mexer nos elementos visuais do ecrã ("activity_main.xml").

## 2. Visão Geral do Sistema
A aplicação tem apenas um ecrã que mostra mensagens de boas-vindas, uma imagem e um calendário. Serve para demonstrar como se organiza o visual da aplicação e como se guardam os textos.

## 3. Arquitetura e Desenho
O projeto usa o modelo básico do Android (Empty Views Activity). O desenho do ecrã usa um sistema de restrições (`ConstraintLayout`) para posicionar o texto, a imagem e o calendário.

## 4. Implementação
Os textos foram retirados do código e guardados no ficheiro `strings.xml` para facilitar alterações futuras. As posições dos elementos foram ajustadas para ficarem centradas e as cores foram definidas no ficheiro `colors.xml`.

## 5. Testes e Validação
A aplicação foi testada num telemóvel virtual (emulador) e num telemóvel físico ligado por cabo, para garantir que os elementos visuais apareciam nos locais corretos.

## 6. Instruções de Utilização
Descarrega o projeto, abre-o no Android Studio e corre a aplicação num emulador ou telemóvel que suporte, no mínimo, a versão 24 do Android (API 24).

# Processo de Desenvolvimento

## 12. Controlo de Versões e Histórico
Neste projeto, devido a algumas dúvidas quanto à criação de um possível repositório (que é o caso deste em questão) todas as alterações que foram realizadas ao longo do projeto ficaram guardadas localmente no disco do meu computador. Mais tarde quando percebi realmente que era necessário criar um repositório para este projeto já tinha feito todas as alterações ao projeto, por isso a existência de um único "commit" dado.

## 13. Dificuldades e Aprendizagens
A maior dificuldade foi perceber como funcionam as "molas" (constraints) para prender os elementos no ecrã e garantir que não ficavam uns em cima dos outros.

## 14. Melhorias Futuras
Uma boa melhoria seria adicionar interatividade aos elementos visuais. Por exemplo, fazer com que a aplicação reaja ao toque mostrando uma pequena mensagem (Toast) quando o utilizador clica na imagem ou escolhe uma data no calendário. Outra melhoria seria adicionar suporte para vários idiomas (internacionalização), traduzindo o ficheiro `strings.xml` para português.

## 15. Declaração de Uso de IA (Obrigatório)
Não utilizei ferramentas de Inteligência Artificial para gerar o código ou o visual desta aplicação. A IA serviu apenas para estruturar o texto deste relatório. Sou totalmente responsável pelo projeto em questão.


