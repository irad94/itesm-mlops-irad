# Virtual Environments

Presents: Irad Olivares

## Installation checklist

To validate the installation of tools, access the following file.

## Activity

In this activity, you will migrate and solve the package issues regarding a notebook that was created in a `Python 3.10.9` version.

Follow the instructions below to do the activity.

### Run the existing notebook

1. Clone the project `https://github.com/carloslme/itesm-mlops-irad.git` on your local computer.
2. Create a virtual environment with `Python 3.10.9`

   * Create venv

     ```
     py -3.10.9 -m venv venv310
     ```
   * Activate the virtual environment using Windows PowerShell

     ```
     venv310/Scripts/Activate.ps1
     ```
3. Install libraries
   Run the following command to install the other libraries.

   ```bash
   pip install -r module-2/session-3/activity/requirements-310.txt
   ```

   Verify the installation with this command:

   ```bash
   pip freeze
   ```
4. Open the `itesm-mlops/module-2/session-3/activity/end_to_end_machine_learning_project.ipynb` notebook and click on `Run All`.

   > **IMPORTANT!**
   > Do not forget to select the Python 3.7.9 kernel you have already created.
   >

   If everything was ok, you should be able to see the last cell with this output:

   ```bash
   Predictions:	 [263527.   331884.02 221119.   ... 105722.   213199.   459125.66]
   ```

**Congrats, the notebook is running in a virtual environment with Python 3.10.9!**
