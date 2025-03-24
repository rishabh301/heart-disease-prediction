<!DOCTYPE html>
<html lang="en">
<head>
    
</head>
<body>
    <div class="container">
        <h1>❤️ Heart Disease Prediction using Machine Learning</h1>
        <h2>📌 Project Overview</h2>
        <p>This project uses Machine Learning to predict whether a person has heart disease based on medical attributes. The trained model analyzes numerical input features and classifies patients as either having heart disease or not.</p>
        <h2>🔍 How It Works</h2>
        <p>Input the following medical parameters into the trained model:</p>
        <ul>
            <li>Age</li>
            <li>Gender</li>
            <li>Chest Pain Type</li>
            <li>Blood Pressure & Cholesterol Levels</li>
            <li>ECG Results</li>
            <li>Heart Rate & More...</li>
        </ul>
        <p>The model then processes the input and returns a **prediction**:</p>
        <code>
        input = (61,1,0,148,203,0,1,161,0,0,2,1,3)
        input_data_as_numpy_array=np.asarray(input)
        input_data_reshape = input_data_as_numpy_array.reshape(1,-1)
        prediction = model.predict(input_data_reshape)
        if (prediction[0]==0):
            print('The person does not have heart disease')
        else:
            print('The person has heart disease')
        </code>
        <h2>🚀 Technologies Used</h2>
        <p>Python, NumPy, Pandas, Scikit-Learn, Machine Learning Algorithms</p>
        <h2>🔗 How to Use</h2>
        <p>1️⃣ Clone the repository:</p>
        <code>git clone https://github.com/YourUsername/Heart-Disease-Prediction.git</code>
        <p>2️⃣ Install dependencies:</p>
        <code>pip install -r requirements.txt</code>
        <p>3️⃣ Run the prediction model:</p>
        <code>python predict.py</code>
        <h2>🌟 Give it a Star ⭐</h2>
        <p>If you like this project, consider giving it a star on GitHub!</p>
    </div>
</body>
</html>
