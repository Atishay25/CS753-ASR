# Team Name - ACDC

- Atishay Jain (210050026)
- Chaitanya Aggarwal (210050038)
- Divyansh Singhal (210050045)
- Cheshta Damor (210050040)
 
# Part 2(A) 
1. CER for zero_shot_whisper_fine_tuned = 0.4706265468281881
2. WER for zero_shot_whisper_fine_tuned = 0.6705675833820948

# Part 2(B) 
1. CER for fine_tuned_whisper_with_constrained_filtering = 0.5576397030089879
2. WER for fine_tuned_whisper_with_constrained_filtering = 0.7653598595669983
The above CER/WER are for N = 10, p = 0.9

# Part 2(C) 
1. CER for fine_tuned_whisper_with_beam_search = 0.47596717467760846
2. WER for fine_tuned_whisper_with_beam_search = 0.6933879461673493

- Please note that we ran our final notebook locally and installed the required pip modules 
  and downloaded the dataset.zip and whisper-small-finetuned.pt once
- Therefore, in our final assgmt2-partII.ipynb, we have commented out those !pip  and !wget lines to avoid installing again and again
- Please uncomment them if you are running freshly where dataset.zip and whisper-small-finetuned.pt are needed