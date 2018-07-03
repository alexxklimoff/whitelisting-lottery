applications.txt: applications list that registered for KYC

passed.txt: applications list that passed KYC

1000 whitelist.txt: 1000 applications that were selected by the lottery

randomly picking winners : sort -R applications.csv | head -n 1000 >1000whitelist.csv
