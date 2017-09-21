# DumPy 
Core version dated 21/09/2017
Nicole Reilly and Jorge Pereda, MCA

Test of some Python code that accesses image files on a local computer (Windows or Linux) and saves images to another local directory.
Also gives an estimate of the time necessary for the operation.
Takes into account the possibility of different file paths and different experimental parameters for different users/OS, saved in separate input files.

Before running:
Update declic_settings_linux.cfg file if using Linux or declic_settings_windows.txt file if using Windows.
Replace file path in quotes after im_path = with path to directory where source images are located.
Replace file path in quotes after save_path = with path to directory where opened images are to be saved.
Be sure the string is terminated by / (Linux) or \\ (Windows) and that Windows paths contain no single \ chars, only \\.
Save file.

Update exp_params.txt file with appropriate parameters for the experiment during which images were taken.
If necessary refer directly back to Declic manips.xls file.
Replace value after moteur = with value of moteur (Column L in .xls file) for the experiment.
Replace value after start_tick = with value of first axial structure image (Column R in .xls file) for the experiment.
Replace value after end_tick = with value of  (Column L in .xls file) for the experiment.
All should be 9-10 digit positive integers not enclosed in quotes.
Save file.

Open Jupyter notebook, find and open Imgsavetimer.ipynb and run!

Note: To avoid overwriting for different users, modified .txt and .cfg files should be added to the .gitignore file in this directory.