# Pacote de tradução Laravel para Português

Pacote de tradução para Português do Brasil

# Como utilizar

De acordo com a documentação do Laravel, a estrutura de localização seria:

```
/lang
----/en
---------messages.php
----/pt
--------messages.php
```

O diretório **lang** fica na raiz do projeto, mas pode ser que você não esteja vendo ele, pois é necessário fazer a publicação antes. Rode o comando abaixo para publicar a pasta **lang**.

```
php artisan lang:publish
```

Agora a pasta **lang** já está disponível, por tanto, dentro dela criei uma pasta chamada **pt**. Baixe ou clone os arquivos deste repositório para dentro da pasta **lang/pt**. Caso utilize o Git, pode executar o comando abaixo.

```
git clone https://github.com/satellasoft/laravel-pacote-lang-portugues.git .
```

Agora nos resta aplicar o pacote de tradução, então abra o arquivo **app/config/app.php** e mude os valores das variáveis abaixo.

```php
//de
'locale' => 'en',
'fallback_locale' => 'en',

//para
'locale' => 'pt',
'fallback_locale' => 'pt',
```

# Créditos

Este pacote foi traduzido pelo **ChatGTP** pelo nosso site https://satellasoft.com.


