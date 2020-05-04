O código foi desenvolvido na linguagem C e o Sistema Operacional que escolhi para executar o processo foi "Ubuntu".

Para executar em seu pc é necessário que jogue aquele comando básico:

-gcc huffman.c

Com este comando compacto o arquivo com a palavra ”ABRACADABRA!” sendo o arquivo de extensão " .txt " :

./huffman -c teste.txt teste.hx

Após a compactação você acaba gerando um arquivo com a extensão " .hx " pode mudar o nome invés de teste para qualquer outro.

Com este comando descompacto o arquivo denominado teste.txt que agora está com este nome: "teste.hx":

./huffman -x teste.hx testao.txt

Voltei o arquivo nomeado "teste.hx" para sua forma original mas coloquei outro nome aleatório "testao.txt" mas repare que após a descompactação o nome do arquivo muda mas o conteúdo interno continua o mesmo.