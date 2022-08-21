# HCRC-CGEL
The data and code of HCRC-CGEL

"On the DEAP database" is the code of HCRC-CGEL conducted in DEAP database.
"On the SEED IV database" is the code of HCRC-CGEL conducted in SEED IV database.


The preprocessed data are shown in:  https://www.scidb.cn/s/bYZBz2
contains:

SEED1, the preprocessed data of the first session of SEED IV database with shape of (851(sample numbers)*15(subjects))*(5(frequency bands)*62(channels));
SEED2, the preprocessed data of the second session of SEED IV database with shape of (832(sample numbers)*15(subjects))*(5(frequency bands)*62(channels));
SEED3, the preprocessed data of the third session of SEED IV database with shape of (822(sample numbers)*15(subjects))*(5(frequency bands)*62(channels));
SEEDlabel1, the corresponding label of SEED1 with shape of (851(sample numbers)*15(subjects))*1;
SEEDlabel2, the corresponding label of SEED2 with shape of (851(sample numbers)*15(subjects))*1;
SEEDlabel3, the corresponding label of SEED3 with shape of (851(sample numbers)*15(subjects))*1;
deap, the preprocessed data of DEAP database with shape of (800(sample numbers)*32(subjects))*(4(frequency bands)*32(channels));
deapa, the labels (arousal) of deap with shape of (800(sample numbers)*32(subjects))*1;
deapa, the labels (arousal) of deap with shape of (800(sample numbers)*32(subjects))*1.
