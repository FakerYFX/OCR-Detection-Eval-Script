# OCR-Detection-Eval-Script
This is an Evaluation script for ocr detection include Precision, Recall and Hmean for your own data.

### How to use

#### Step 1:

pip install -r requirements.txt

#### Step 2:

Prepare your own gt file and result file, make sure the number of the samples in both files is the same. The format is just like the gt.json and result.json.

#### Step 3:

python script.py -g=gt.json -s=submit.json



