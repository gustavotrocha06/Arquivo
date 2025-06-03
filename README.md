REFLEXÃO FINAL

1 - Se você tentar ler um arquivo que não existe usando FileReader, o Java lançará uma exceção do tipo FileNotFoundException. Isso ocorre porque o Java não consegue localizar o caminho ou o arquivo especificado no momento da leitura.
2 - O try-with-resources é uma forma de garantir que os recursos (como arquivos) sejam fechados automaticamente após o uso, mesmo que ocorra uma exceção. O código fica mais limpo e legível, e possiu uma menor chance de esquecer de fechar o recurso.
3 - Para CSV, você pode usar BufferedWriter/BufferedReader e escrever os dados separados por vírgulas. Para JSON, você pode usar bibliotecas como Gson (do Google) ou Jackson para transformar objetos em JSON e vice-versa.
