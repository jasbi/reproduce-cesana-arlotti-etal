
############ DATA FILTERED OF EXPERIMENTS 1-6 (INFANTS): Looking time by trial ############

% These are the .txt files that contains the infants' filtered looking time data in response to the outcome in Experiments 1-6  (see main text and SOM).

Experiment1: 19-month-old infants, file name "E1-byTrial".
Experiment2: 12-month-old infants, file name "E2-byTrial".
Experiment3: 19-month-old infants, file name "E3-byTrial".
Experiment4: 12-month-old infants, file name "E4-byTrial".
Experiment5: 19-month-old infants, file name "E5-byTrial".
Experiment6: 12-month-old infants, file name "E6-byTrial".
	

% In each file, data were stored with the following columns:

	Participant % Participants' ID number.
	
	Trial % The trial corresponding to the data point.	
	
	Outcome	% The type of outcome (inconsistent, consistent; see main text and SOM).

            Couple   %   The pair of objects used in the trial (see main text and SOM).

            Distance %   The initial distance of the scooped object from the cup (see main text and SOM). 
	
	LookingTime % Cumulative looking time at the outcome.
		



############ DATA FILTERED OF EXPERIMENTS 3-6 (INFANTS): looking time difference and oculomotor responses by participant ############

% These are the .txt files that contains the filtered infants' difference in looking time at the two outcome types (inconsistent, consistent) and oculomotor responses in the deduction
phase (shift, gaze X-position and pupil change) by participant in Experiments 3-6  (see main text and SOM).

Experiment3: 19-month-old infants, Inference Condition, file name "E3-byParticipant".
Experiment4: 12-month-old infants, Inference Condition, file name "E4-byParticipant".
Experiment5: 19-month-old infants, No_Inference Condition, file name "E5-byParticipant".
Experiment6: 12-month-old infants, No_Inference Condition, file name "E6-byParticipant".
	

% In each file, data were stored with the following columns:

	Participant % Participants' ID number.
	
	LTDiff % the difference of the looking time at the inconsistent and consistent
outcomes (see main text and SOM)

             Shift % the proportion of trials in which at least one gaze shift to the cup was executed during the potential deduction phase (see main text and SOM)
	
	X	% The average gaze position on the X-axis across the effect window  (see main text and SOM).

           PD   %   The average change in pupil diameter from the baseline across the effect window (see main text and SOM).

        
         

############ DATA FILTERED OF EXPERIMENTS 3-6 (INFANTS): oculomotor responses by temporal bin of 17ms ############

% These are the .txt files that contains the infants' oculomotor responses (gaze X-position and pupil change) during the Potential Deduction Phase (see main text and SOM).

Experiment3: 19-month-old infants, Inference Condition, file name "E3-byBin".
Experiment4: 12-month-old infants, Inference Condition, file name "E4-byBin".
Experiment5: 19-month-old infants, No_Inference Condition, file name "E5-byBin".
Experiment6: 12-month-old infants, No_Inference Condition, file name "E6-byBin".
	

% In each file, data were stored with the following columns:

	Participant % Participants' ID number.

            Trial % The trial corresponding to the data point.	
             
            Bin	% Indicates the frame in which the data was collected by the Eyectracker (60 Hz)
	
	MovieID % Unique Scenes ID 

          Experiment %  indicates the age group and the Inference vs No_Inference condition

          X	% The average gaze position on the X-axis in the corresponding bin (see main text and SOM).

           PD   %   The average change in pupil diameter from the baseline in the corresponding Bin (see main text and SOM).




############ DATA FILTERED OF EXPERIMENT 7 (ADULTS) ############

% These are the .txt files that contains the adults' data in Experiment 7 during the Potential Deduction Phase (see main text and SOM).

(Screen Stands refers to the scenes in which an object exits twice from behind the occluder -common to infants' Experiments 3-6. Screen Lowers refers to the scenes in which the occluder lowers and the object inside the cup is revealed - common to infants' Experiments 1 and 2.) These data allow to perform the temporal analysis for both the Pupil and EyeGaze in all the Conditions (Inference, No Inference type-1, No Inference type-2) and Movie Type (Screen stands and Screen Lowers). 

Inf_NoInf2_ScUp_Pup  % Pupil data. MovieType: screen stands. Data from: Inference and No Inference type2 conditions . 
Inf_NoInf1_ScUp_Pup	 % Pupil data. MovieType: screen stands. Data from: Inference and No Inference type1 conditions.
Inf_NoInf1_ScDown_Pup	% Pupil data. MovieType: screen lowers. Data from: Inference and No Inference type1 conditions.
Inf_NoInf2_ScUp_MeanX % Eye gaze data. MovieType: screen stands. Data from: Inference and No Inference type2 conditions.
Inf_NoInf2_ScDown_Pup % Pupil data. MovieType: screen lowers. Data from: Inference and No Inference type2 conditions.
Inf_NoInf1_ScUp_MeanX % Eye gaze data. MovieType: screen stands. Data from: Inference and No Inference type1 conditions.
Inf_NoInf1_ScDown_MeanX % Eye gaze data. MovieType: screen lowers. Data from: Inference and No Inference type1 conditions.
Inf_NoInf2_ScDown_MeanX % Eye gaze data. MovieType: screen lowers. Data from: Inference and No Inference type2 conditions.
	

% In each file, data were stored with the following columns:

	Participant	% Participants' number 
	
	PhaseLabel 	% The phase corresponds to the Potential Deduction Phase (see Main Text, Fig.2)	
	
	Bin		% Indicates the frame in which the data was collected by the Eyectracker (60 Hz)
	
	MovieID 	% Unique Scenes ID 
		
	InferenceCondition	% Inference scenes are coded as 1, No inference scenes are coded as 0
	
	Count % counts the number of unique MovieID 	
	
	MeanPupil OR  MeanX  	% These are the dependent measures. MeanPupil are the pupil values baseline corrected. In the file, they are arranged by Participant, Bin and MovieID. MeanX column contains the gaze position in the X-axis per Participant, Bin and MovieID. 
	

