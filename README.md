# Self_Study
# Here_I _Write_My_self_study_codes
# Here is a code that gives us the number of  Omani_Governorates:

def number_of_Omani_Governorates():
    Omani_Governorates = ['Ad Dakhiliyah', 'Al-Dhahirah', 'Al Batinah North', 'Al Batinah South','Al Buraimi Governorate', 'Al Wusta Governorate', 'Ash-Sharqīyah North Governorat', 'Dhofar Governorate','Ash-Sharqīyah South Governorate', 'Muscat', 'Musandam Governorate']
    count = 0
    
    for Governorate in Omani_Governorates:
        count += 1
    
    return count
    
numberofGovernorateinOman = number_of_Omani_Governorates()
print("number_of_Omani_Governorates:", numberofGovernorateinOman)
