Reconhecimento de entidades atrav�s do Spacy.

No arquivo datasets.rar est�o compactados os datasets necess�rios para o processamento ao treino e teste.
Para esse estudo de caso, dois modelos s�o treinados para reconhecerem a entidade FOOD, posteriormente, a quantidade de acertos e a previs�o
No modelo 1, est� sendo treinado apenas as entidades foods, descartando as entidades que j� vem com o spacy. Al�m disso, o treino e teste s�o dados gerados a partir de algumas frases fixas, mudando apenas o nome que configura aquela entidade.
No modelo 2, o treinamento est� habilitado tanto para o reconhecimento de entidades foods, quanto as entidades j� salvas no modelo. Para isso, foi usado as v�rias palavras do arquivo food e textos do arquivo articles.

