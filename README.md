# Palpation-Training-v1
Palpation Training

<br>

## Run the project

1. Open the Scene in Unity ```Assets/Scenes/Palpation22222``` (This scene is the modification version of the ```Palpation``` Scene from the original git)

2. Change the HoloLens IPv4 address in the python script ```Assets/Scripts/PatientDialogGPT.py```:

   ```python
   ip = 'your hololens ipv4 address'
   port = 5000
   ```

3. The TCP connection between HoloLens and GPT is on scripts ```HoloLensClient.cs```  and  ```PatientDialogGPT.py``` in directory ```Assets/Scripts``` .

