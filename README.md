

## Stopword-Helper

        stopwords bash script for 13 languages

.......................................................................


## available languages:


       |-----------------------------------------------------------|
       | Language   | ISO code | default encoding | also available |
       |-----------------------------------------------------------|
       |  Danish    | da       | ISO-8859-1       | UTF-8          |
       |  Dutch     | nl       | ISO-8859-1       | UTF-8          |
       |  English   | en       | ISO-8859-1       | UTF-8          |
       |  Finnish   | fi       | ISO-8859-1       | UTF-8          |
       |  French    | fr       | ISO-8859-1       | UTF-8          |
       |  German    | de       | ISO-8859-1       | UTF-8          |
       |  Hungarian | hu       | ISO-8859-1       | UTF-8          |
       |  Italian   | it       | ISO-8859-1       | UTF-8          |
       |  Norwegian | no       | ISO-8859-1       | UTF-8          |
       |  Portuguese| pt       | ISO-8859-1       | UTF-8          |
       |  Spanish   | es       | ISO-8859-1       | UTF-8          |
       |  Swedish   | sv       | ISO-8859-1       | UTF-8          |
       |  Russian   | ru       | KOI8-R           | UTF-8          |
       |-----------------------------------------------------------|


###  run like:
      $:./stopWordByLang da
      $:./stopWordByLang nl
      $:./stopWordByLang en
      $:./stopWordByLang fi
      $:./stopWordByLang fr
      $:./stopWordByLang de
      $:./stopWordByLang hu
      $:./stopWordByLang it
      $:./stopWordByLang no
      $:./stopWordByLang pt
      $:./stopWordByLang es
      $:./stopWordByLang sv
      $:./stopWordByLang ru

### Instal

     git clone https://github.com/santex/Stopword-Helper;
     cd Stopword-Helper;
     dzil build;
     dzil test;
     sudo dzil install;

### test english stopwords

     stopWordByLang en
