# R-Assignment
#Data Inspection
Fang_et_al_genotypes.txt
> dim(fang_et_al_genotypes)
[1] 2782  986
> head(fang_et_al_genotypes)
# A tibble: 6 × 986
  Sample_ID JG_OTU   Group abph1.20 abph1.22 ae1.3 ae1.4 ae1.5 an1.4 ba1.6
  <chr>     <chr>    <chr> <chr>    <chr>    <chr> <chr> <chr> <chr> <chr>
1 SL-15     T-aust-1 TRIPS ?/?      ?/?      T/T   G/G   T/T   C/C   ?/?  
2 SL-16     T-aust-2 TRIPS ?/?      ?/?      T/T   ?/?   T/T   C/C   A/G  
3 SL-11     T-brav-1 TRIPS ?/?      ?/?      T/T   G/G   T/T   ?/?   G/G  
4 SL-12     T-brav-2 TRIPS ?/?      ?/?      T/T   G/G   T/T   C/C   G/G  
5 SL-18     T-cund   TRIPS ?/?      ?/?      T/T   G/G   T/T   C/C   ?/?  
6 SL-2      T-dact-1 TRIPS ?/?      ?/?      T/T   G/G   T/T   C/C   A/G  
# ℹ 976 more variables: ba1.9 <chr>, bt2.5 <chr>, bt2.7 <chr>,
#   bt2.8 <chr>, Fea2.1 <chr>, Fea2.5 <chr>, id1.3 <chr>, lg2.11 <chr>,
#   lg2.2 <chr>, pbf1.1 <chr>, pbf1.2 <chr>, pbf1.3 <chr>, pbf1.5 <chr>,
#   pbf1.6 <chr>, pbf1.7 <chr>, pbf1.8 <chr>, PZA00003.11 <chr>,
#   PZA00004.2 <chr>, PZA00005.8 <chr>, PZA00005.9 <chr>,
#   PZA00006.13 <chr>, PZA00006.14 <chr>, PZA00008.1 <chr>,
#   PZA00010.5 <chr>, PZA00013.10 <chr>, PZA00013.11 <chr>, …
# ℹ Use `colnames()` to see all variable names
> nrow(fang_et_al_genotypes)
[1] 2782
> ncol(fang_et_al_genotypes)
[1] 986
#Snp
> > dim(snp)
[1] 983  15
> head(snp)
# A tibble: 6 × 15
  SNP_ID  cdv_marker_id Chromosome Position alt_pos mult_positions amplicon
  <chr>           <dbl> <chr>      <chr>    <chr>   <chr>          <chr>   
1 abph1.…          5976 2          27403404 NA      NA             abph1   
2 abph1.…          5978 2          27403892 NA      NA             abph1   
3 ae1.3            6605 5          1678897… NA      NA             ae1     
4 ae1.4            6606 5          1678896… NA      NA             ae1     
5 ae1.5            6607 5          1678898… NA      NA             ae1     
6 an1.4            5982 1          2404985… NA      NA             an1     
# ℹ 8 more variables: cdv_map_feature.name <chr>, gene <chr>,
#   `candidate/random` <chr>, Genaissance_daa_id <dbl>,
#   Sequenom_daa_id <dbl>, count_amplicons <dbl>, count_cmf <dbl>,
#   count_gene <dbl>
> nrow(snp)
[1] 983
> ncol(snp)
[1] 15
