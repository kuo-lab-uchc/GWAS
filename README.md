# UK Biobank Proteomic Aging GWAS
1. UK Biobank genetically determined Europeans after exlucding those with poor-quality genotype data (n=43,707)
2. Missing proteins imputed uising the k-nearest neightbors approach (k=10)
3. PAC, HPS, and a second-generation brain-specific clock developed to predict mortaility were derived following the references below.
a) Kuo CL, Chen Z, Liu P, Pilling LC, Atkins JL, Fortinsky RH, Kuchel GA, Diniz BS. Proteomic aging clock (PAC) predicts age-related outcomes in middle-aged and older adults. Aging Cell. 2024 Aug;23(8):e14195. doi: 10.1111/acel.14195. Epub 2024 May 15. PMID: 38747160; PMCID: PMC11320350.
b) Kuo CL, Liu P, Drouard G, Vuoksimaa E, Kaprio J, Ollikainen M, Chen Z, Pilling LC, Atkins JL, Fortinsky RH, Kuchel GA, Diniz BS. A proteomic signature of healthspan. medRxiv [Preprint]. 2025 Jan 28:2024.06.26.24309530. doi: 10.1101/2024.06.26.24309530. PMID: 38978645; PMCID: PMC11230312.
c) Goeminne LJE, Vladimirova A, Eames A, Tyshkovskiy A, Argentieri MA, Ying K, Moqri M, Gladyshev VN. Plasma protein-based organ-specific aging and mortality models unveil diseases as accelerated aging of organismal systems. Cell Metab. 2025 Jan 7;37(1):205-222.e6. doi: 10.1016/j.cmet.2024.10.005. Epub 2024 Nov 1. PMID: 39488213.
5. GWAS performed using REGENIE adjusting for age, sex, age*sex, age^2*sex, genotyping arrary type, baseline assessment center, top 20 genetic principal components
