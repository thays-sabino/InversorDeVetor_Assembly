# Inversão de Vetor em Assembly (x32)

Este projeto em **MIPS Assembly (32-bit)**, desenvolvido no **simulador MARS**, demonstra a manipulação de dados na memória através da **inversão de um vetor** de 5 númeoros inteiros.

_**Arquitetura:**_ MIPS 32-bit (utilizando a **syscall** para entrada e saída).  
_**Alocação:**_ ambos os vetores (`vet1` e `vet2`) são alocados na seção **.data** usando a diretiva `.word`, reservando **20 bytes (5 inteiros × 4 bytes)**.  
_**Lógica de Endereçamento:**_ acessa os elementos do vetor utilizando o **endereço base + offset (índice × 4)** .  

O intuito desse projeto é colocar em prática comandos aprendidos na matéria de _**Organização de Computadores (IF-MG)**_ até o momento, o que implica em um número limitado de comandos que podem ser usado.

## **Operações**

O código realiza **três operações principais**:

1. **Leitura:** solicita e armazena 5 números inteiros fornecidos pelo usuário no `vet1`.  
2. **Inversão:** gera o `vet2` contendo os mesmos 5 números, mas em ordem invertida em relação ao `vet1`.  
3. **Exibição:** imprime na tela o conteúdo completo do `vet1` (**ordem original**) e, em seguida, o conteúdo do `vet2` (**ordem inversa**).  


## **Como executar no simulador MARS**

Salve esse projeto com a extensão `.asm` em uma pasta de sua preferência **->** abra o simulador **MARS** e na aba "FILE" procure por "Open..." (CTRL + o ) **->** após o arquivo ser carregado, clique em "RUN" (F5) **->** a janela do console (RUN I/O) na parte inferior da tela, solicitará que você digite os **5 inteiros**, um de cada vez, pressionando **Enter** após cada número **->** após a leitura, o programa exibirá os elementos do `vet1` e do `vet2` na mesma janela.  

---

Desenvolvido por _**[Thays](https://github.com/thays-sabino)**_ 🌸  
