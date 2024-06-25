# DescobertaDeFarmacos

## Arquivos de entrada:
Aceita gbk e embl
<img src="https://user-images.githubusercontent.com/53004506/61376046-3a698500-a898-11e9-98e9-b8edabe052e1.png" alt="gbk">


fasta

<img src="https://i0.wp.com/bioinformaticamente.com/wp-content/uploads/2021/01/Schermata-del-2021-01-16-15-20-40.png?resize=616%2C268&ssl=1" alt="fasta">

## Comandos importantes
antismash -h : Pedir ajuda ao software

antismash --help-showall : Ajuda completa

--taxon bacteria ou fungos

--output-dir NomeDaPastaDeSaida

--genefinding-tool prodigal

--hmmdetection-strictness strict,relaxed e loose (HMM-based cluster detection)
                        
## Linha de comando

antismash brevi_brevis.gbk --taxon bacteria --output-dir saida --fullhmmer --tigrfam --cc-mibig --cb-knownclusters --pfam2go --rre  --cb-subclusters --asf 
