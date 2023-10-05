# Self_Study
# Here_I _Write_My_self_study_codes
# Here is a code that gives us the number of  Omani_Governorates:

def number_of_Omani_Governorates():
    Omani_Governorates = ['Ad Dakhiliyah', 'Al-Dhahirah', 'Al Batinah North', 'Al Batinah South','Al Buraimi Governorate', 'Al Wusta Governorate', 'Ash-Sharqīyah North Governorate', 'Dhofar Governorate',' Ash-Sharqīyah South Governorate', 'Muscat', 'Musandam Governorate']
    count = 0
    
    for Governorate in Omani_Governorates:
        count += 1
    
    return count
    
numberofGovernorateinOman = number_of_Omani_Governorates()
print("number_of_Omani_Governorates:", numberofGovernorateinOman)


# In the coming code I will use next_up() function to return the first Governorate in the list Omani_Governorates: here is the link for this code https://jupyter.org/try-jupyter/lab?path=notebooks%2Fnext_up%28%29+function.ipynb 

def next_up():
    Omani_Governorates = ['Ad Dakhiliyah', 'Al-Dhahirah', 'Al Batinah North', 'Al Batinah South',' Al Buraimi Governorate', 'Al Wusta Governorate', 'Ash-Sharqīyah North Governorate', 'Dhofar Governorate',' Ash-Sharqīyah South Governorate', 'Muscat', 'Musandam Governorate']
        
    if len(Omani_Governorates) > 0:
        return Omani_Governorates[0]
    else:
         return  None 
         
Governorates = ['Ad Dakhiliyah', 'Al-Dhahirah', 'Al Batinah North', 'Al Batinah South'] 
first_Governorate = next_up()

if first_Governorate is not None:
    print(f'Next Governorate up: {first_Governorate}')
else:
    print('The list of Governorate is empty.')
# This code returns my favorite Governorate:
https://anaconda.cloud/api/nbserve/launch_notebook?nb_url=https%3A%2F%2Fanaconda.cloud%2Fapi%2Fprojects%2F9927dc2b-b614-4854-ad37-13a87a70e9f6%2Fversions%2F608cb24b-ddb1-4acb-9229-5249eda0cd7c%2Ffiles%2Ffavorite%20Governorate%20.ipynb      
<a target="_blank" href=https://anaconda.cloud/api/nbserve/launch_notebook?nb_url=https%3A%2F%2Fanaconda.cloud%2Fapi%2Fprojects%2F9927dc2b-b614-4854-ad37-13a87a70e9f6%2Fversions%2F608cb24b-ddb1-4acb-9229-5249eda0cd7c%2Ffiles%2Ffavorite%20Governorate%20.ipynb><img 




 # I am using the capitalize() function to capitalize the first letter in a list :
https://anaconda.cloud/api/nbserve/launch_notebook?nb_url=https%3A%2F%2Fanaconda.cloud%2Fapi%2Fprojects%2Ff149c59f-6990-448a-a3ab-aee38d488e5d%2Fversions%2F82cd8266-0e43-47ad-aeb0-5ee7b3a9403d%2Ffiles%2Fcapitalize().ipynb 
