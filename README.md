# Lab-5_202001436

Static Analysis Tool : mypy
<br>
Git repository used: https://github.com/CT83/SmoothStream.git
<br>
Language: python
<br>
<h2>1. constants.py</h2>
<br>
<strong>Output:</strong>
<br>
<img src= "https://user-images.githubusercontent.com/118917278/227482869-99c83e92-59b5-401c-8b94-937abbc6eca4.png"></img>

<br>
<strong>Explaination of errors:</strong>
<br>
utils.py:48: error: Cannot find implementation or library stub for module named "cv2"  [import]
<br>
-It shows we can't implement the module because it is not installed, to remove this error we have to import the module named "cv2".
<br>
-Here mypy found 1 error in 1 file. <br>

<h2>2. Streamer.py</h2>
<strong>Output:</strong>
<br>

<img src= "https://user-images.githubusercontent.com/118917278/227494756-b0d96c2b-d509-403f-81d7-3adb6cf01084.png"></img>

<br>
<strong>Explaination of errors:</strong>
<br>
-Here mypy couldn't find 3 modules "cv2", "imutils" and "imutils.video" .
<br>
- Here 5 errors are found in 3 files. <br>

<h2>3. StreamViewer.py</h2>
<strong>Output:</strong>
<br>
<img src= "https://user-images.githubusercontent.com/118917278/227490113-78178447-1655-4fc7-a37c-6023bce1ec20.png"></img>

<br>
<strong>Explaination of errors:</strong>
<br>
- Here mypy couldn't find 2 modules named "cv2". <br>
- Here 2 errors are found in 2 files. <br>

<h2>4. test_local_streaming.py</h2>
<strong>Output:</strong>
<br>
<img src= "https://user-images.githubusercontent.com/118917278/227491623-f0bf0453-e56f-46ad-82f6-c87a36ea2c6b.png"></img>

<strong>Explaination of errors:</strong>

<br>
- Here mypy couldn't find 3 modules "cv2", "imutils" and "imutils.video" .
<br>
- Here 6 errors are found in 4 files. <br>

<h2>5. utils.py</h2>
<br>
<strong>Output:</strong>
<br>

<img src= "https://user-images.githubusercontent.com/118917278/227492483-f2ac423e-6b2f-4789-8541-8772ba18b1dc.png"></img>
<br>
<strong>Explaination of errors:</strong>

<br>
- Here mypy couldn't find module "cv2".
<br>
-Here mypy found 1 error in 1 file.
<br>
<br>
<br>
