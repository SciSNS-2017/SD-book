# Sistemi Dinamici
Appunti del corso _Introduzione ai Sistemi Dinamici_, raccolti durante l'anno accademico 2018-2019. I docenti del corso sono:
* Stefano Marmi
* Daniele Tantari
* Fracensco Grotto
* Ugo Bindini

### Struttura del progetto
Abbiamo provato a riorganizzare i trascritti delle lezioni ospitati [qui](https://github.com/SciSNS-2017/Sistemi-Dinamici) in un libro più strutturato e in cui gli argomenti trattati sono ordinati dal punto di vista dei contenuti e non in ordine cronologico. Questa è una prima bozza, incompleta e meno aggiornata rispetto ai trascritti delle lezioni.

Attualmente i file sono:
* `main.tex`: è il file principale della repository. Vengono importati tutti pacchetti necessari e ci sono le impostazioni generali del progetto. 
* `style.sty`: contiene tutte le impostazioni di stile del progetto, include alcuni pacchetti e definisce nuovi comandi, ambienti theorem ecc. utili per velocizzare la scrittura e uniformare lo stile.
* `bibliografia.bib`: contiene la bibliografia.
* `chapters/[chapter-name].tex`: contenuto dei vari capitoli.
* `chapters/appendix/[appendix-name].tex`: contenuto delle appendici ()

### Autori dei capitoli
|**#**|**Titolo**          |**Docente**|**Tipo**|**Scrittore**                              |
|---- |--------------------|-----------|--------|-------------------------------------------|
|1    |Introduzione        |Marmi      |chapter |@alepiazza, @marco-venuti, @arna4          |
|2    |Dinamica Topologica |Marmi      |chapter |@marco-venuti, @alepiazza, @arna4, @Konnoi5|
|3    |Dinamica Misurabile |Marmi      |chapter |@alepiazza, @marco-venuti                  |
|4    |Frazioni Continue   |Marmi      |chapter |                                           |
|5    |Entropia            |Marmi      |chapter |                                           |
|6    |Catene di Markov    |Tantari    |chapter |                                           |
|5    |Meccanica Statistica|Tantari    |chapter |                                           |
|A    |Teoria della misura |Grotto     |appendix|@marco-venuti, @Konnoi5                    |
|B    |Spazi di Hilbert    |Bindini    |appendix|@alepiazza, @marco-venuti                  |


### Come scrivere una lezione
A causa delle immagini il tempo di compilazione di `main.tex` può essere molto lungo. Quando includi un'immagine scrivi `\iffigureon` prima di `\begin{figure}` e `\fi` dopo `\end{figure}`. Se nel preambolo di `main.tex` scrivi `\figureontrue` dopo `\newif\iffigureon` le figure verranno incluse; se invece scrivi `\figureonfalse` le immagini non compariranno nel pdf e la compilazione sarà più veloce.

