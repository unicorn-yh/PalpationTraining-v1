# Palpation-Training-v1
Palpation Training

<br>

## Run the project

1. Open the Unity project.

2. Open the Scene in Unity ```Assets/Scenes/Palpation22222``` (This scene is the modification version of the ```Palpation``` Scene from the original git [PalpationTraining.git](https://github.com/wudongwudong/PalpationTraining.git) )

3. Change the HoloLens IPv4 address in the python script ```Assets/Scripts/PatientDialogGPT.py```:

   ```python
   ip = 'your hololens ipv4 address'
   port = 5000
   ```

4. The TCP connection between HoloLens and GPT is on scripts ```HoloLensClient.cs```  and  ```PatientDialogGPT.py``` in directory ```Assets/Scripts``` .

5. Build the project on ARM64 and Local Machine in Build Settings in Unity.

6. Run the build in Visual Studio.

7. After successfully deploy and build the project on HoloLens, run the python script  ```PatientDialogGPT.py```  to get connection with HoloLens. (GPT API might be malfunctioning occasionally)

   

