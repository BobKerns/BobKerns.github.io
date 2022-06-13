# Some Basic Biology about mRNA

There are many reasons why someone might fail to learn this basic biology in 7th grade science class. If you are out sick with a virus, you might not learn about how viruses work!

So a bit of remediation, so you can understand this tweet.

<!-- markdownlint-disable MD033 -->
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">The vax has mRNA for one protein.<br>The virus has mRNA for that one + 28 more.<br>The vax mRNA is quickly destroyed by the body.<br>The virus keeps making more complete copies of itself.</p>&mdash; Bob (Moderna #4) Kerns (@BobKerns) <a href="https://twitter.com/BobKerns/status/1535917069878718464?ref_src=twsrc%5Etfw">June 12, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<!-- markdownlint-enable MD033 -->

This discussion is about the mRNA vaccines. There are other types of vaccine, which I will not discuss further here.

* Protein-based vaccines contain viral proteins for the immune system to recognize.
* Killed-virus vaccines contain the whole virus, killed.  These contains the complete set of proteins.
* Attenuated-virus vaccines contain live virus that has been weakened so it does not cause disease. The virus triggers your cells to produce enough viral proteins to trigger immunity.
* Viral vector vaccines contain a live non-disease-causing virus which contains genes for viral proteins from the disease-causing virus. The virus triggers your cells to produce enough viral proteins to trigger immunity.

The mRNA vaccines differ from these in that they contain mRNA for a single protein, which your cell then produces, until the mRNA is destroyed by the cell.

## What is mRNA?

mRNA (Messenger RNA) is the link between a cell's DNA and creating proteins.

DNA consists of sequences of 4 elements, abbreviated G, T, A, and C. DNA has two paired strands. If one strand has a G, the other has a T, and vise versa. Likewise for A and C. These make up the "alphabet" of genetics. They function in groups of three; each group of 3 codes for a specific amino acid to be used in constructing the protein.

RNA usually consists of one strand (mRNA always does). Rather than T, RNA uses U, but otherwise it functions the same, in groups of three.

To construct a protein, the first step is to *transcribe* the DNA into RNA, so G becomes U, T becomes G, A becomes C, and C becomes A in the RNA.

After a bit of editing, this is transported to the ribosomes—the protein factories of the cell. This is the mRNA.

Each mRNA has some extra stuff at the begining and end that I'll skip to keep things simple. I'm also going to skip to the amino acids coded by each group of 3. This makes the sequences $\frac{1}{3}$ as long. The letters for the amino acids are:

> A R N D B C Q E Z G H I L K M F P S T W Y V

[![Amino Acid Table](../assets/images/Aminoacids_table.svg.png)](/assets/images/Aminoacids_table.svg)

## How does a virus work?

A virus is a small particle containing some genetic material, some structural proteins, and some lipids (oils). It gains entry to cells, where the genetic material and the initial proteins work together with the cell's own machinery to make new copies of the virus.

There are different types of virus, using different types of genetic matieral—single or double stranded, DNA or RNA.

The RNA viruses can be *positive sense* or *negative sense*. Positive sense viruses have RNA that directly codes for proteins, as mRNA. Negative sense viruses have RNA that has to be re-transcribed to positive sense mRNA to function.

SARS-Cov-2 (the virus for COVID-19) is a positive-sense virus.

The genetic material codes the additional proteins the virus needs, both as part of the virus particles and to replicate. The newly-formed virus particles then escape from the cell, usually killing the cell in the process.

In the case of positive-sense RNA viruses, the genetic material from the virus cannot become part of the host cell genome, as can happen with some DNA viruses.

## So what is in the mRNA vaccines

I've taken the data from [here](https://github.com/NAalytics/Assemblies-of-putative-SARS-CoV2-spike-encoding-mRNA-sequences-for-vaccines-BNT-162b2-and-mRNA-1273/blob/main/Figure1Figure2_032321.fasta). These were sequenced by people outside the companies (and in the case of the BioNTech/Pfizer vaccine, confirmed by the company).

Here's the amino acid sequence for the BioNTech/Pfizer BNT-162b2 vaccine

```fasta
MFVFLVLLPLVSSQCVNLTTRTQLPPAYTNSFTRGVYYPDKVFRSSVLHS
TQDLFLPFFSNVTWFHAIHVSGTNGTKRFDNPVLPFNDGVYFASTEKSNI
IRGWIFGTTLDSKTQSLLIVNNATNVVIKVCEFQFCNDPFLGVYYHKNNK
SWMESEFRVYSSANNCTFEYVSQPFLMDLEGKQGNFKNLREFVFKNIDGY
FKIYSKHTPINLVRDLPQGFSALEPLVDLPIGINITRFQTLLALHRSYLT
PGDSSSGWTAGAAAYYVGYLQPRTFLLKYNENGTITDAVDCALDPLSETK
CTLKSFTVEKGIYQTSNFRVQPTESIVRFPNITNLCPFGEVFNATRFASV
YAWNRKRISNCVADYSVLYNSASFSTFKCYGVSPTKLNDLCFTNVYADSF
VIRGDEVRQIAPGQTGKIADYNYKLPDDFTGCVIAWNSNNLDSKVGGNYN
YLYRLFRKSNLKPFERDISTEIYQAGSTPCNGVEGFNCYFPLQSYGFQPT
NGVGYQPYRVVVLSFELLHAPATVCGPKKSTNLVKNKCVNFNFNGLTGTG
VLTESNKKFLPFQQFGRDIADTTDAVRDPQTLEILDITPCSFGGVSVITP
GTNTSNQVAVLYQDVNCTEVPVAIHADQLTPTWRVYSTGSNVFQTRAGCL
IGAEHVNNSYECDIPIGAGICASYQTQTNSPRRARSVASQSIIAYTMSLG
AENSVAYSNNSIAIPTNFTISVTTEILPVSMTKTSVDCTMYICGDSTECS
NLLLQYGSFCTQLNRALTGIAVEQDKNTQEVFAQVKQIYKTPPIKDFGGF
NFSQILPDPSKPSKRSFIEDLLFNKVTLADAGFIKQYGDCLGDIAARDLI
CAQKFNGLTVLPPLLTDEMIAQYTSALLAGTITSGWTFGAGAALQIPFAM
QMAYRFNGIGVTQNVLYENQKLIANQFNSAIGKIQDSLSSTASALGKLQD
VVNQNAQALNTLVKQLSSNFGAISSVLNDILSRLDPPEAEVQIDRLITGR
LQSLQTYVTQQLIRAAEIRASANLAATKMSECVLGQSKRVDFCGKGYHLM
SFPQSAPHGVVFLHVTYVPAQEKNFTTAPAICHDGKAHFPREGVFVSNGT
HWFVTQRNFYEPQIITTDNTFVSGNCDVVIGIVNNTVYDPLQPELDSFKE
ELDKYFKNHTSPDVDLGDISGINASVVNIQKEIDRLNEVAKNLNESLIDL
QELGKYEQYIKWPWYIWLGFIAGLIAIVMVTIMLCCMTSCCSCLKGCCSC
GSCCKFDEDDSEPVLKGVKLHYT
```

Here it is for the Moderna mRNA-1273 vaccine

```fasta
MFVFLVLLPLVSSQCVNLTTRTQLPPAYTNSFTRGVYYPDKVFRSSVLHS
TQDLFLPFFSNVTWFHAIHVSGTNGTKRFDNPVLPFNDGVYFASTEKSNI
IRGWIFGTTLDSKTQSLLIVNNATNVVIKVCEFQFCNDPFLGVYYHKNNK
SWMESEFRVYSSANNCTFEYVSQPFLMDLEGKQGNFKNLREFVFKNIDGY
FKIYSKHTPINLVRDLPQGFSALEPLVDLPIGINITRFQTLLALHRSYLT
PGDSSSGWTAGAAAYYVGYLQPRTFLLKYNENGTITDAVDCALDPLSETK
CTLKSFTVEKGIYQTSNFRVQPTESIVRFPNITNLCPFGEVFNATRFASV
YAWNRKRISNCVADYSVLYNSASFSTFKCYGVSPTKLNDLCFTNVYADSF
VIRGDEVRQIAPGQTGKIADYNYKLPDDFTGCVIAWNSNNLDSKVGGNYN
YLYRLFRKSNLKPFERDISTEIYQAGSTPCNGVEGFNCYFPLQSYGFQPT
NGVGYQPYRVVVLSFELLHAPATVCGPKKSTNLVKNKCVNFNFNGLTGTG
VLTESNKKFLPFQQFGRDIADTTDAVRDPQTLEILDITPCSFGGVSVITP
GTNTSNQVAVLYQDVNCTEVPVAIHADQLTPTWRVYSTGSNVFQTRAGCL
IGAEHVNNSYECDIPIGAGICASYQTQTNSPRRARSVASQSIIAYTMSLG
AENSVAYSNNSIAIPTNFTISVTTEILPVSMTKTSVDCTMYICGDSTECS
NLLLQYGSFCTQLNRALTGIAVEQDKNTQEVFAQVKQIYKTPPIKDFGGF
NFSQILPDPSKPSKRSFIEDLLFNKVTLADAGFIKQYGDCLGDIAARDLI
CAQKFNGLTVLPPLLTDEMIAQYTSALLAGTITSGWTFGAGAALQIPFAM
QMAYRFNGIGVTQNVLYENQKLIANQFNSAIGKIQDSLSSTASALGKLQD
VVNQNAQALNTLVKQLSSNFGAISSVLNDILSRLDPPEAEVQIDRLITGR
LQSLQTYVTQQLIRAAEIRASANLAATKMSECVLGQSKRVDFCGKGYHLM
SFPQSAPHGVVFLHVTYVPAQEKNFTTAPAICHDGKAHFPREGVFVSNGT
HWFVTQRNFYEPQIITTDNTFVSGNCDVVIGIVNNTVYDPLQPELDSFKE
ELDKYFKNHTSPDVDLGDISGINASVVNIQKEIDRLNEVAKNLNESLIDL
QELGKYEQYIKWPWYIWLGFIAGLIAIVMVTIMLCCMTSCCSCLKGCCSC
GSCCKFDEDDSEPVLKGVKLHYT
```

Both are 1273 amino acids long—the Moderna vaccine is named for the length.

## What mRNA is in the virus?

There are a total of 10 genes that code a total of 29 different proteins. Of these 29 proteins, four are structural, making up part of the virus particles themselves. These are:

* Envelope (E)
* Membrane (M)
* Nucleocapsid (N)
* Spike (S)

The other proteins are needed for replication and interaction with the host cell, but do not become part of the virus.

Here is the spike protein from the final version of the virus first sequenced in [January of 2020 (2nd update)](https://www.ncbi.nlm.nih.gov/nuccore/MN908947):

```fasta
MFVFLVLLPLVSSQCVNLTTRTQLPPAYTNSFTRGVYYPDKVFRSSVLHS
TQDLFLPFFSNVTWFHAIHVSGTNGTKRFDNPVLPFNDGVYFASTEKSNI
IRGWIFGTTLDSKTQSLLIVNNATNVVIKVCEFQFCNDPFLGVYYHKNNK
SWMESEFRVYSSANNCTFEYVSQPFLMDLEGKQGNFKNLREFVFKNIDGY
FKIYSKHTPINLVRDLPQGFSALEPLVDLPIGINITRFQTLLALHRSYLT
PGDSSSGWTAGAAAYYVGYLQPRTFLLKYNENGTITDAVDCALDPLSETK
CTLKSFTVEKGIYQTSNFRVQPTESIVRFPNITNLCPFGEVFNATRFASV
YAWNRKRISNCVADYSVLYNSASFSTFKCYGVSPTKLNDLCFTNVYADSF
VIRGDEVRQIAPGQTGKIADYNYKLPDDFTGCVIAWNSNNLDSKVGGNYN
YLYRLFRKSNLKPFERDISTEIYQAGSTPCNGVEGFNCYFPLQSYGFQPT
NGVGYQPYRVVVLSFELLHAPATVCGPKKSTNLVKNKCVNFNFNGLTGTG
VLTESNKKFLPFQQFGRDIADTTDAVRDPQTLEILDITPCSFGGVSVITP
GTNTSNQVAVLYQDVNCTEVPVAIHADQLTPTWRVYSTGSNVFQTRAGCL
IGAEHVNNSYECDIPIGAGICASYQTQTNSPRRARSVASQSIIAYTMSLG
AENSVAYSNNSIAIPTNFTISVTTEILPVSMTKTSVDCTMYICGDSTECS
NLLLQYGSFCTQLNRALTGIAVEQDKNTQEVFAQVKQIYKTPPIKDFGGF
NFSQILPDPSKPSKRSFIEDLLFNKVTLADAGFIKQYGDCLGDIAARDLI
CAQKFNGLTVLPPLLTDEMIAQYTSALLAGTITSGWTFGAGAALQIPFAM
QMAYRFNGIGVTQNVLYENQKLIANQFNSAIGKIQDSLSSTASALGKLQD
VVNQNAQALNTLVKQLSSNFGAISSVLNDILSRLDKVEAEVQIDRLITGR
LQSLQTYVTQQLIRAAEIRASANLAATKMSECVLGQSKRVDFCGKGYHLM
SFPQSAPHGVVFLHVTYVPAQEKNFTTAPAICHDGKAHFPREGVFVSNGT
HWFVTQRNFYEPQIITTDNTFVSGNCDVVIGIVNNTVYDPLQPELDSFKE
ELDKYFKNHTSPDVDLGDISGINASVVNIQKEIDRLNEVAKNLNESLIDL
QELGKYEQYIKWPWYIWLGFIAGLIAIVMVTIMLCCMTSCCSCLKGCCSC
GSCCKFDEDDSEPVLKGVKLHYT

```

Individual variants have mutations that can make alter how well the spike protein works to enter cells. Despite small differences, these are variants of the same virus.

Here's a map of where the proteins are coded:

![SARS-Cov-2 Proteme](../assets/images/SARS-CoV-2-proteome.jpg)

## How long does mRNA persist?

In mammalian cells, between hours and days. Longer-lived mRNA can be transcribed into more protein molecules, but is slower to turn on and off.

It is important that mRNA be destroyed, so genes can be turned on and off to maintain the correct level of each protein.

Since mRNA is continuously created by active genes, it would otherwise accumulate. Life would be impossible.

mRNA vaccines begin producing protein shortly after injection. This production quicly declines as the mRNA is destroyed. The viral proteins produced then activate the immune system, before they, too, are destroyed.

## How long does a virus last?

Each virus, once it gains entry to a cell, produces multiple copies. If it produces 10 on average, after one generation we'd have 10, after 2, 100, and so on. 6 generations would give 1,000,000 virus particles, and 11,111 dead cells to produce them (across all generations).

This obviously cannot continue forever. One of two things happens:

1. The host organism dies.
2. The immune system gets ramped up and starts killing viruses and infected cells.

If the second, the viral growth is stopped or slowed. For most viruses, the virus can be completely eliminated, but there are many which persist and even become lifelong.

But without having seen the viral proteins before, it takes considerable time for the immune system to ramp up, and so the first phase of an infection is characterized by exponential growth of the viral population.
