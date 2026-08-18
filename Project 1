# hackbio_biocomputing-task
praise_sope@cloudshell:~$ echo "praise saint-john"
praise_sope@cloudshell:~$ mkdir praise #creating directory
praise_sope@cloudshell:~$ mkdir biocomputing && cd biocomputing #creating and changing directory
praise_sope@cloudshell:~/biocomputing$ wget https://raw.githubusercontent.com/HackBio-Internship/Bash_NGS_Starters/refs/heads/main/biocomp_samp/wildtype.fna
praise_sope@cloudshell:~/biocomputing$ wget https://raw.githubusercontent.com/HackBio-Internship/Bash_NGS_Starters/refs/heads/main/biocomp_samp/wildtype.gbk
praise_sope@cloudshell:~/biocomputing$ wget https://raw.githubusercontent.com/HackBio-Internship/Bash_NGS_Starters/refs/heads/main/biocomp_samp/wildtype.gbk
praise_sope@cloudshell:~/biocomputing$ mv wildtype.fna praise #moving .fna to praise
praise_sope@cloudshell:~/biocomputing$ rm wildtype.gbk.1 #removing duplicate
praise_sope@cloudshell:~/biocomputing$ 
#Confirm if the .fna file in dir praise is mutant or wild type
if grep -i "tatatata" "../praise/wildtype.fna"; then
    echo "The .fna file is MUTANT."
else
    echo "The .fna file is WILD TYPE."
fi
praise_sope@cloudshell:~/biocomputing$ if grep -i "tatatata" "../praise/wildtype.fna"; then #Print all saved lines in new file
    grep -i "tatatata" "../praise/wildtype.fna" > "../praise/mutant_matches.txt"
    echo "Matching lines saved to mutant_matches.txt"
fi
praise_sope@cloudshell:~/biocomputing$ ls -lh ../praise/ #Ensure that file was saved in praise
praise_sope@cloudshell:~/biocomputing$ tail -n +2 wildtype.gbk | wc -l #number of lines excluding the header in the .gbk file
praise_sope@cloudshell:~/biocomputing$ grep "^LOCUS" wildtype.gbk | head -1 | awk '{print $3}' #sequence length from the LOCUS line
praise_sope@cloudshell:~/biocomputing$ grep "^SOURCE" wildtype.gbk | head -1
praise_sope@cloudshell:~/biocomputing$ grep '/gene=' wildtype.gbk #all gene names
praise_sope@cloudshell:~/biocomputing$ ls -lh  #list of files in dir
praise_sope@cloudshell:~/biocomputing$ ls -lh ../praise/ #files in praise
