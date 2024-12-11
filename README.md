# AI-Video-and-Image-Generation
Assignment submitted by Varadraj Kharosekar to Persist Ventures for Artificial Intelligence (AI) internship|

This script uses PyTorch, Transformers, and Diffusers libraries to generate animations based on user-provided prompts and configuration parameters. The script is designed to produce creative visual outputs using AI-driven models.

## How to Use
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
(Alternatively, activate the included virtual environment if shared.)

Run the script:

bash
Copy code
python Untitled-1.py "YOUR_PROMPT" --user_id YOUR_USER_ID --iterations 10 --seed 42 --fps 30
Replace:

YOUR_PROMPT with the desired text description.
YOUR_USER_ID with a unique user identifier.
The output animation will be saved in the current working directory.

Script Arguments
prompt: The text description for the animation.
--user_id: (Required) Unique identifier for the user.
--iterations: Number of iterations for image refinement (default: 10).
--seed: Random seed for reproducibility (default: 42).
--fps: Frames per second for the animation (default: 30).

Requirements
Python 3.9+
Libraries:
PyTorch
Transformers
Diffusers
Pickle-Mixin
ffmpeg-python
Example
bash
Copy code
python Untitled-1.py "A boy walking on a sunny day" --user_id 12345 --iterations 10 --seed 42 --fps 30
Notes
Ensure ffmpeg is installed and available in your system's PATH.
The output directory and filenames can be customized in the script.

Submit any issues or questions by raising an issue in this repository.

ON https://github.com/varadraj6055/AI-Video-and-Image-Generation 
