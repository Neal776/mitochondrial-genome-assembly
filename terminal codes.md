cd novoplasty
ls
zmore Damag_R1.fq.gz 
ls
more config_plasty_Damag.txt
s
ls
zmore Damag_R1.fq.gz 
grep -c '@A00155' Damag_R1.fq.gz 
clear
zgrep -c '@A00155' Damag_R1.fq.gz 
zmore Damag_R1.fq.gz
clear
ls
zgrep -c '@A00155' Damag_1.fastq.gz 
bg
ls
zcat Damag_1.fastq.gz | head -n 32000000 > test_damag_R1.fq
more test_damag_R1.fq
ls
grep -c '@A00155' test_damag_R1.fq 
more Seed.fasta 
ls
more NC_024511.2.fasta
ls
more CP_assembly.sh
clear
more CP_assembly.sh
ls
mkdir old
mv MEL.* test_damag_R1.fq Uncircularized_assemblies_1_Damag.fasta Damag_C* old/
ls
rm -f log_Damag.txt 
ls
* 
bowtie2-build -f NC_024511.2.fasta MEL
more CP_assembly.sh 
ls
ls -l
./CP_assembly.sh Damag &
ls
ll -rt
rm -f Contigs_1_Damag.fasta
cd old/
ls
more Uncircularized_assemblies_1_Damag.fasta
ls
more ls
ls
cd ..
ls
cat Damag_R1.fq.gz > nombre_R1.fq.gz
ls
more CP_assembly.sh
ls
history 
history > novoplasty_test.txt
