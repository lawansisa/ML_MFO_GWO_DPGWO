# ML_MFO_GWO_DPGWO
This respository will help the readers to download 22 GLCM Features extracted from 115 MFL Crack Images from SGT along with (NoteBook) Python Codes for three 
meta-heursitic algorithms namely Moth Flame Optimization (MFO), Grey Wolf Optimization (GWO) and Dynamic Population Grey Wolf Optimization (DPGWO) algorithms
to select the number of features and its combinations using XGB Regressor() Machine Learning Model
Download the datasets target_all.csv and all_features.csv files
Store in your local drive and note down the path
Change the path in the given below statments
ds_tar1=pd.read_csv('d:/msk/jack data/target_all.csv') # Table 1: Dataset of 115 MFL Crack Images’ …..
ds_fea=pd.read_csv('d:/msk/jack data/all_features.csv') # Table 2: Dataset of 115 MFL Crack Image’s 22…..
Change 0 as 1 to predict depth and 2 to predict width in the givne below statement
ds_tar = ds_tar1.iloc[:,0] #for length change 1 to depth and 2 to width
Change no. of moths in n_sample, no. of features in nof and maximum iteration in nitr
n_sample = 50 #number of Moths
nof = 17 #no. of features change this between 15 and 22
nitr = 20 #number of iterations
Change maximum sample number m_sample greater than n_sample value
