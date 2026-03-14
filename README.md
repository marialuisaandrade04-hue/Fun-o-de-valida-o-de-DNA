# Fun-o-de-valida-o-de-DNA
# Análise de DNA em Python

Este repositório contém funções simples de bioinformática.

Funções incluídas:
- validação de sequência de DNA
- contagem de nucleotídeos
nucleotideos = ["A" , "C" , "G" , "T"]

# Funcao de validacao de sequencia 
def validateSeq(dna_seq):
  tmpseq = dna_seq.upper()
  for nuc in tmpseq:
    if nuc not in nucleotideos:
      return False
  return tmpseq
