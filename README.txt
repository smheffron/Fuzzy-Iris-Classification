Understanding the code:
	1.) FuzzyLogic.ipynb is where all the generalized code for fuzzy operations,
	cylindrical closure for combining antecedents, implication operators, fuzzy
	implications, compositional rule of inference, defuzzification, real valued
	operations (chopping consequents, get min firing strength, etc), aggregations, and
	trapezoidal membership function creators is located.
	
	2.) IrisClassifier.ipynb is where I use the generalized logic system in
	FuzzyLogic.ipynb to classify 150 different samples of 3 different kinds of irises
	based on several different attributes defined in the UCI dataset.


How to run the code:
	1.) Ensure that all ipynb files are in the same directory. IrisClassifier.ipynb
	requires usage from FuzzyLogic.ipynb. Upload these files to Jupyter for usage.
	Also make sure that the iris.data file is in the same directory.
	
	2.) To run the classifier on the UCI iris dataset, open IrisClassifier.ipynb in
	Jupyter
	
	3.) Click on Cell->run all


Understanding the output:
	1.) The code will output a 3x3 confusion matrix where row/column 1 is Iris Setosa,
	row/column 2 is Iris Versicolour, and row/column three is Iris Virginica.
	
	2.) It will also output a final accuracy value as a percentage of of irises that
	were successfully classified by the fuzzy system based on their label in from the
	dataset.