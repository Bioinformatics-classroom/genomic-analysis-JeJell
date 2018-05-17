# UE génétique médicale 2018-05-17
* Jean Jellimann
* Chloé Salerno
## Exercice 1
### Q1
Le génome de référence (GRCh 37)
### Q2
Sur le chromosome 18
### Q3
NC_000018.9:g.52895531T>C devient NM_001243236.1:c.1449A>G par exemple (il y a d'autres  transcrits dans la base de donnée de Mutalyser qui présentent cette variation).

NC_000018.9:g.52999284delG devient NM_001243232.1:c.336+18306delC par exemple (il y a d'autres  transcrits dans la base de donnée de Mutalyser qui présentent cette variation).

NC_000018.9:g. 53331929C>A ne possède pas de transcrit dans la base de donnée de Mutalyser. On suppose que c'est une mutation rare ou qu'elle est hors de l'exon.
rmq : en fait, Mutalyser utilise RefSeq. Or il n'y a pas de variant dans la base de donnée de RefSeq, mais il y en a un dans Ensembl (voir Q5). C'est donc une mutation très rare.


Les deux premières mutations sont transcrites en ARNm tandis que la troisième n'est pas transcrite.
La mutation T>C devient A>G, donc le brin trancrit est le brin anti-sens.

### Q4
Pour NC_000018.9:g.52895531T>C : fréquence (génome) = 0.3747 (exome : fréquence = 0.3750)
Pour NC_000018.9:g.52999284delG : fréquence = 0.02478 (exome : no variant)
Pour NC_000018.9:g. 53331929C>A : genome : no variant; exome : fréquence = 8.164e-6

### Q5
La première mutation est aussi fréquente dans le génome que dans l'exome. Elle est donc dans l'exome : elle est donc transcrite. Mais c'est une mutation synonyme.
La deuxième mutation n'existe pas dans l'exome : elle n'est donc pas transcrite.
La troisième mutation est transcrite (elle est tellement rare que la base de donnée SNIP n'a pas de variant similaire dans ses génomes).

### Q6
La première mutation est transcrite mais fréquente.
La troisième mutation est transcrite et est très rare (question 3 et 4). Comme elle est rare, elle est plus probablement pathologique. Elle induit l'apparition d'un codon stop. C'est donc celle là qui mérite une étude plus approfondie.


## Exercice 2
# Q1
La mutation est dans le gène SHOX.
# Q2
SHORT STATURE HOMEOBOX : le gène SHOX est associé à des petites tailles et le syndrome de Turner (qui qui cause une petite taille). Le gène est présent à la fois sur le chromosome X et Y : c'est un gène pseudoautosomique. 
Maladies associées :
-Short stature, idiopathic familial (autosomique récessif)
-Leri-Weill dyschondrosteosis (autosomique dominant)
-Short stature, idiopathic familial (on ne connait pas le mode de transmission)
# Q3
Le syndrome de Turner correspond à une monosomie de l'X. Le patient atteint n'a donc qu'une copie du gène SHOX. Cela induit une petite taille (haplo-insuffisance).
# Q4
NM_000451.3:c.399G>C devient NC_000023.10:g.595474G>C au niveau génomique.
# Q5
NC_000023.10:g.595474G>C
NC signifie qu'il s'agit d'ADN (données génomiques)
000023.10 signifie que la mutation fait partie du chromosome 23 (X) et qu'il s'agit de la dixième version de ce gène.
g. signifie qu'il s'agit des données génomiques.
595474 signifie que la mutation concerne le 595474ième nucléotide du chromosome.
G>C signifie qu'il s'agit d'une transposition où une guanine est remplacée par C.
# Q6
La notation HGVS au niveau de la protéine est NM_000451.3(SHOX_i001):p.(Glu133Asp)
# Q7
NM_000451.3(SHOX_i001):p.(Glu133Asp)
NM_ signifie qu'il s'agit d'ARNm
000451.3 signigie que le numéro de transcrit du gène est 451 et qu'il s'agit de la 3ième version.
(SHOX_i001) signifie qu'on est dans le gène SHOX (et isoforme).
p. signifie qu'on s'intéresse aux données protéomiques.
(Glu133Asp) signifie que le Glutamate en position 133 devient un acide Aspartique.
# Q8
Il s'agit d'une mutation faux-sens (un acide glutamique devient acide aspartique).
# Q9
http://genome.ucsc.edu/cgi-bin/hgTracks?db=hg19&lastVirtModeType=default&lastVirtModeExtraState=&virtModeType=default&virtMode=0&nonVirtPosition=&position=chrX%3A595464%2D595484&hgsid=669215893_Qxa6YZ7Lyxihwircf9ck4Ci7ExwQ
# Q10
La mutation est le changement d'un G vers un C. Or dans le génome de réference, le nucléotide correspondant est un G. Il s'agit donc du brin sens.
# Q11
Le gène SHOX comporte 6 exons.
# Q12
La mutation se trouve dans l'exon 3.
# Q13
C'est une région très conservée car il s'agit d'un exon.
# Q14
Le variant se trouve dans le domaine fonctionnel "HomeoBox Domain".
# Q15
Cette mutation a déjà été décrite dans la publication :
"Short stature before puberty: which children should be screened for SHOX deficiency?" de Wolters B.
# Q16
Ce variant peut donner :
- un variant non-sens avec une probabilité de 86 %
- un variant dans un exon non-codent avec une probabilité de 14 %
# Q17
# Q18
# Q19
http://wannovar.wglab.org/done/159923/lL2GfKVXN_uIjR0J/index.html
# Q20
Le DOI de cet article est 10.1038/gim.2015.30
# Q21
Les critères déterminant une variation pathogène sont (entre autres) :
* 1. la variation est absente dans les populations des bases de données
* 2. la prévalence chez les patients atteints est statistiquement augmentée par rapport aux sujets controles
* 3. le variant modifie la longueur de la protéine
* 4. Un changement du même acide-aminé peut donner un variant pathogénique établi
* 5. il s'agit d'un point chaud de mutations ou d'un domaine fonctionnelle bien étudié qui n'a pas de mutation bénignes.
* 6. de bonnes études fonctionnelles montrent un effet délétère
* 7. des études de co-ségrégation avec la maladie dans de nombreuses familles atteintes montrent un lien fort entre la variation et la pathologie
* 8. la mutation est de novo (en confirmant si possible la paternité et la maternité)
# Q22
* Une publication (Q19) montre qu'une mutation sur le même acide aminé donne une pathologie : PS 1
* La mère est atteinte, ce n'est donc pas une mutation de novo.
* Sur GNOMAd, le variant X-595474 (qui correspond à cette mutation) n'est pas répertorié : PM 2
* Sur OMIM : "They also identified a functionally significant SHOX mutation (312865.0001) by screening 91 individuals with idiopathic short stature" : PS 4
On a deux PS, la mutation est donc pathogénique.
