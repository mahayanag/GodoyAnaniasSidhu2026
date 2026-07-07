Repository contains the following files and folders:



**FOLDER: files_experiment**

Folder with all files necessary to run the experiment described in the paper.


**ldt_1803.psyexp**
Code for running the experiment on psychopy (version 2026.1)

**stimuli.csv**
Table with experimental stimuli, 

	Variables are: 

	‘word’: the stimuli presented to participants;
	‘cond’: the stimuli’s condition - iconic onomatopoeic words (onom), iconic non-onomatopoeic words 	(icon), non-iconic (nicon) and pseudo words (pseudo)
	‘correct’: whether the correct response for the stimuli was pressing the key p or q

**treinamento.xlsx**
Table with stimuli used in the practice section

**error.mp3**
Sound file with the auditory stimuli presented to participant when they made an incorrect judgement

**FOLDER: analyses**

Folder with all files necessary to replicate the statistical analyses described in the experiment.

**raw_data_all_subjects.csv**

Complete data for all three experimental conditions for all 40 participants in the study (n = 120 per participant). Data for pseudowords not used in the analyses and not included in the dataset, following the same guidelines for data sharing and data analyses as the original study. Raw data is not provided to ensure participant anonymity.

Variables in the dataset are:

"word": the experimental stimuli        
"participant": participant ID  
"trial_n": order of presentation           
"cond": the stimuli’s condition - iconic onomatopoeic words (onom), iconic non-onomatopoeic words 	(icon), non-iconic (nicon) and pseudo words (pseudo)             
"correct_key": whether the correct response for the stimuli was pressing the key p or q
"key_pressed": key pressed by participant      
"answer": whether participant pressed the correct key (1) or not (0)             
"rt": reaction time               
"freq_corp_log": log-frequency (Soares et al. 2018)
"freq_corp_abs_log": absolute frequency (Soares et al. 2018)
"ort_nlet": length measured as the number of letters          
"ort_neig_dl": orthographic levenshtein distance (Soares et al. 2018)      
"ort_big_p_tk_med": mean bigram probability 
"icon_m": iconicity (Godoy, 2026)            
"concreteness": concreteness (Santos et al. 2017)     
"AoA": age of acquisition (Santos et al. 2017)          
"POS": part-of-speech - nouns (n) and verbs (v) 


**analysis_final_report.html:** a report including codes and results for all analyses on reaction time and accuracy

**analysis_final_report.Rmd:** code to generate analysis_final_report.html. It allows for the replication of all analyses using raw_data_all_subjects.csv as the input file
