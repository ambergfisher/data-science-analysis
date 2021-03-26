# Data Analysis Report

This was an analysis for my Intro to Data Science course I did recently. The professor gave us four sets of data, which varied in size. He then asked us to classify the data using models of four types (which he gave us). Beyond those requirements, we were given free range to choose the specific libraries and models. My analysis is found in the PDF document entitled `Report` while the actual code is in the Jupyter notebook entitled `data-analysis.ipynb`. You might be able to see the code with the traditional IPython kernel, but you won't be able to run anything unless you install Julia to your computer and add the IJulia package (Julia kernel for Jupyter). The data can be viewed in the `original_data` folder.

# Julia and Scikit-Learn
At the beginning of the semester, the professor chose to use Julia as our class language. Julia is advertised as a high-level language similar to Python in its ease of use with a comparable speed to low-level languages like C. However, although Julia has some performance benefits in some areas over Python, it fails to implement some popular libraries that make Python so attractive for machine learning. Julia does have a Scikit-Learn library but much of the functionality is simply imported from Python. Ultimately, I find that eliminates any potential speed increases that may have existed before. Thus, if I were to do this project on my own time, I would have absolutely written it with the traditional Python Scikit-Learn library. Also, any code that seems odd (the DataFrameMapper comes to mind; also choosing the LinearSVC over the traditional SVC model) are likely a result of the Python to Julia conversion.

# Models (Required kind - Specific model choice)
1. Naive Bayes classifier - GaussianNB
2. Support Vector Machines - LinearSVC with Bagging
3. Classification trees of some sort - Random Forest
4. Neural Network - MLPClassifier
