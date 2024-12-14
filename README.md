
# Install necessary packages
# Create a virtual environment
python -m venv venv

# Activate the virtual environment

# On Windows
venv\Scripts\activate
# On Unix or MacOS
source venv/bin/activate

# Install the requirements
pip install -r requirements.txt

# Load models used 
Models are provided in the assessment.ipynb file

# list all pretrained clip models
open_clip.list_pretrained()

# Load fine-tuned clip models
models/model.pt#   E v a l u a t i n g - Z S L - v s - M L  
 