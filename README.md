#### O código foi desenvolvido na linguagem C
> - Sistema Operacional escolhido foi "Ubuntu".
>> Para executar necessita-se o comando:
>> - **-gcc huffman.c**
>> Para Compactar arquivo de extensão " .txt " :
>> - **./huffman -c teste.txt teste.hx**

Após a compactação você acaba gerando um arquivo com a extensão " .hx " pode mudar o nome invés de teste para qualquer outro.

Com este comando descompacto o arquivo denominado teste.txt que agora está com este nome: "teste.hx":

./huffman -x teste.hx testao.txt

Voltei o arquivo nomeado "teste.hx" para sua forma original mas coloquei outro nome aleatório "testao.txt" mas repare que após a descompactação o nome do arquivo muda mas o conteúdo interno continua o mesmo.