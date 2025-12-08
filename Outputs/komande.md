# komande.md

*Ve�ba 6*

## >>> README.md

### 1.5 - 1.9 - uneti komande

```bash
tar -xzf za_vezbe_Klebsiella_sekvence.tar.gz
cd za_vezbe_Klebsiella_sekvence/
mkdir -p ../data/{genomes,annotations}
mv *.fna ../data/genomes
mv *.gff ../data/annotations
cd ..
```

---

## >>> klebsiella_demonstracija_prosirena.md

### 4.1 - uneti *output* komandi, a ne komande

```bash
1,52,60,67,71,73

# Prika�ite izdvojene kolone za Strain, Virulence score, iucA, iroB, rmpA
 i rmpA2:
strain         iucA  iroB  rmpA     virulence_score  rmpA2
GCF_017743115  1     1     2        4                rmpA2_5-54%
GCF_017743135  9     6     11       4                -
GCF_017815715  1     1     2        3                rmpA2_5-54%
GCF_021057265  1     -     27       4                rmpA2_6*-47%
GCF_021442005  1     -     40*-47%  4                rmpA2_3-47%
GCF_902723695  1     1     2        4                rmpA2_2*-54%
GCF_902723705  1     1     2        4                rmpA2_4*-34%
GCF_902827215  2     4     82-19%   5                -
```

### 4.4 - uneti *output* komandi, a ne komande

```bash
# Upi�ite brojeve kolona koje izdvajate:1,71,98

# Prika�ite izdvojene kolone za Strain, Virulence score i Resistance score
strain         virulence_score  resistance_score
GCF_017743115  4                0
GCF_017743135  4                0
GCF_017815715  3                0
GCF_021057265  4                1
GCF_021442005  4                2
GCF_902723695  4                2
GCF_902723705  4                1
GCF_902827215  5                0

# Odaberite 1 soj koji je samo hipervirulentan (+ ima rmpA2):
GCF_017815715
# Upi�ite informaciju o njegovoj virulentnosti/rezistentnosti sa NCBI/Genome:
hipervirulentan
# Odaberite 1 soj koji je hipervirulentan i multirezistentan (+ ima iroB):
GCF_902723695
# Upi�ite informaciju o njegovoj virulentnosti/rezistentnosti sa NCBI/Genome
: Carbapenem resistant and hypervirulent
```

### 5.3 - uneti komande

```bash

```

### 2 - uneti komande

```bash

```

### 3 - uneti komande

```bash

```

### 4 - uneti komande i sadrzaj klebsiella_download_archive.sh fajla

```bash

```
